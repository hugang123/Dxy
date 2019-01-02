# Dxy
Caculate the genetic distance of Dxy(like Fst) between the two populations form the vcf file .

usage: win_Dxy.py [-h] -v vcf -p poplist [-w window [default:100000]]
                  [-s step [default:50000]] [-o output [default:Dxy.txt]]

Calculate Dxy form the vcf(.gz) between the two populations.

optional arguments:
          -h, --help            show this help message and exit

          -v vcf                vcf file with gz format

          -p poplist            input the two populations file,each row represent one pop 
                                Example:
                                        pop1:Sampl1	sample2
                                        pop2:Sample3 Sample4

          -w window [default:100000]
                                window size

          -s step [default:50000]
                                step size

          -o output [default:Dxy.txt]
                                output file
