1..254 | ForEach-Object {
  $ip = "192.168.1.$_"
  $result = Test-NetConnection -ComputerName $ip -Port 554 -WarningAction SilentlyContinue
  if ($result.TcpTestSucceeded) {
    Write-Host "RTSP port open at: $ip"
break
  }
}

rtsp://admin:admin@<IP>:554/live/ch00_0

rtsp://admin:admin@192.168.1.180:554/live/ch00_

