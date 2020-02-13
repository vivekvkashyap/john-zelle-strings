# john-zelle-strings




def main():
   months="JanFebMarAprMayJunJulAugSepOctNovDec"
   n=int(input("enter the number:"))
   pos=(n-1)*3
   month_abbrev=months[pos:pos+3]
   print("the month abbreviation is",month_abbrev)
main()
