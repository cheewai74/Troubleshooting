https://www.computerhope.com/issues/ch001617.htm

Type diskpart 
At the DISKPART> prompt, type list disk and press Enter.
E.g: select disk 1.
attributes disk

# Disable USB Read Only
attributes disk clear readonly  

# Lock USB Drive.
attributes disk set readonly
