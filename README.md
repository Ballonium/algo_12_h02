# algo_12_h02
Aufgabendaten:
  RAM-Programm:
    01: READ 1
    02: LOAD *1
    03: JGTZ 6
    04: WRITE 0
    05: GOTO 22
    06: LOAD *1
    07: STORE 2
    08: LOAD *1
    09: SUB 1
    10: STORE 3
    11: LOAD *3
    12: JGTZ 14
    13: GOTO 21
    14: LOAD *2
    15: MULT *1
    16: STORE 2
    17: LOAD *3
    18. SUB 1
    19: STORE 3
    20: GOTO 11
    21: WRITE 2
    22: HALT
    
Aufgabenstellung:
(a) Beschreiben Sie was das Programm macht.

(b) Nehmen Sie an, dass a = σ(1),x = σ(2),b =
    σ(3) gilt und geben Sie eine Invariante an, die
    in den Zeilen 11 und 21 gilt.
    
(c) Schreiben Sie ein RAM Programm, welches die
    Fakultät berechnet
