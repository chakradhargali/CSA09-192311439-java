# Task02 - Part A2: Buffered I/O

- Student: G.Chakradhar
- Register number: 192311439
- Java version: Microsoft OpenJDK 17.0.20

`analysis-and-pseudocode.md` provides the required call prediction, buffered redesign, operating-system explanation, limitation and comparison with `Files.readAllLines()`.

Result: a 50 MiB byte-at-a-time reader performs 52,428,800 successful Java `read()` calls (plus the EOF check), while a 64 KiB buffer needs only about 800 buffer refills plus EOF.
