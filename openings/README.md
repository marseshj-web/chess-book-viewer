# Opening names

`openings.txt` is built from the Lichess opening list, https://github.com/lichess-org/chess-openings (CC0 1.0, public domain).

Each line is `board turn castling<TAB>ECO<TAB>name`, where the key holds the first three FEN fields of the position after the opening's moves. When several lines reach the same position, the shortest line's name is kept. The app matches positions rather than move orders, so transpositions are found too.
