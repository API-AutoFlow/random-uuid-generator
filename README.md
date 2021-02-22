# uuid-generator
Randoom UUID Generator

This solution was created for a customer who needed to create random UUID for Postgres.


1. While loop (run it 32 times)
2. Inside the while loop use Action Integer/Random (between 0~15)
3. Match condition (10-> A, 11->B, 12-> C->13 ~~~~~~)
4. Action Array/Insert-At to create an array with all 32 Hexadecimals
5. Array Join to create a single string