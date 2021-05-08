# Code Vigenère by Léo

The key is "I LOVE MEMES" and the message do decrypt is "QQE VND E KMIIYY OESNZ"

The table is as below:

 X |A | Z |  B |  Y |  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N
------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|
A|A | Z |  B |  Y |  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N
Z | Z |  B |  Y |  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A
B |  B |  Y |  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z
Y|  Y |  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B
C|  C |  X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y
X|   X |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C
D |  D |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X
W  |  W  | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D
E   | E  | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W
V   | V |  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E
F|  F |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V
U |  U |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F
G |  G |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U
Y |  Y |  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G
H|  H |  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y
S|  S |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H
I |  I |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S
R |  R |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I
J |  J |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R
Q |  Q |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J
K  |  K |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q
P  |  P |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q|  K
L   |  L |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q|  K|  P
O   |  O |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q|  K|  P|  L
M |  M |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q|  K|  P|  L|  O
N |  N |A| Z |  B |  Y | C |   X|  D|  W | E| V |  F|  U|  G |  Y |  H|  S |  I|  R|  J|  Q|  K|  P|  L|  O|  M
