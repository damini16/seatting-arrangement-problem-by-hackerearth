# seatting-arrangement-problem-by-hackerearth
from sys import stdin, stdout
 
seats = ['12 WS\n', '11 MS\n', '10 AS\n', '9 AS\n', '8 MS\n', '7 WS\n', '6 WS\n', '5 MS\n', '4 AS\n', '3 AS\n', '2 MS\n', '1 WS\n', '24 WS\n',
         '23 MS\n', '22 AS\n', '21 AS\n', '20 MS\n', '19 WS\n', '18 WS\n', '17 MS\n', '16 AS\n', '15 AS\n', '14 MS\n', '13 WS\n', '36 WS\n',
         '35 MS\n', '34 AS\n', '33 AS\n', '32 MS\n', '31 WS\n', '30 WS\n', '29 MS\n', '28 AS\n', '27 AS\n', '26 MS\n', '25 WS\n', '48 WS\n',
         '47 MS\n', '46 AS\n', '45 AS\n', '44 MS\n', '43 WS\n', '42 WS\n', '41 MS\n', '40 AS\n', '39 AS\n', '38 MS\n', '37 WS\n', '60 WS\n',
         '59 MS\n', '58 AS\n', '57 AS\n', '56 MS\n', '55 WS\n', '54 WS\n', '53 MS\n', '52 AS\n', '51 AS\n', '50 MS\n', '49 WS\n', '72 WS\n',
         '71 MS\n', '70 AS\n', '69 AS\n', '68 MS\n', '67 WS\n', '66 WS\n', '65 MS\n', '64 AS\n', '63 AS\n', '62 MS\n', '61 WS\n', '84 WS\n',
         '83 MS\n', '82 AS\n', '81 AS\n', '80 MS\n', '79 WS\n', '78 WS\n', '77 MS\n', '76 AS\n', '75 AS\n', '74 MS\n', '73 WS\n', '96 WS\n',
         '95 MS\n', '94 AS\n', '93 AS\n', '92 MS\n', '91 WS\n', '90 WS\n', '89 MS\n', '88 AS\n', '87 AS\n', '86 MS\n', '85 WS\n', '108 WS\n',
         '107 MS\n', '106 AS\n', '105 AS\n', '104 MS\n', '103 WS\n', '102 WS\n', '101 MS\n', '100 AS\n', '99 AS\n', '98 MS\n', '97 WS']
 
 
rez = [seats[int(stdin.readline())-1] for _ in range(int(stdin.readline()))]
stdout.write(''.join(rez))
