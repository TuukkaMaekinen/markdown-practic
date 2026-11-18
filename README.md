# Movies - My favorite hobby

My favorite hobby is movies. I watch them and I write about them. Movies are not only my *hobby*, they are my **passion**.
I also host movie quiz in local pub at every Thursday.

## My favorite movies Top-5:

1. Dumb and Dumber (1994)
2. the Straight story (1999)
3. The Big Lebowski (1998)
4. Happiness (1998)
5. Modern Times (1936)

## My favorite directors:

- Peter & Bobby Farrelly
- Wes Anderson
- Joel & Ethan Coen
- Martin Scorsese
- David Cronenberg
- Jeff Nichols
- Terry Gilliam
- Paul Verhoeven
- Luis Buñuel
- Billy Wilder

### Directors' best movies

| Director | Movie |
| ----------- | ----------- |
| Peter & Bobby Farrelly | Dumb and Dumber (1994) |
| Wes Anderson | Rushmore (1998) | 
| Joel & Ethan Coen | The Big Lebowski (1998) |
| Martin Scorsese | GoodFellas (1990) |
| David Cronenberg | A History of Violence (2005) |
| Jeff Nichols | Mud (2012) |
| Terry Gilliam | The Fisher King (1991) |
| Paul Verhoeven | Turkish Delight (Turks Fruit, 1973) |
| Luis Buñuel | The Discreet Charm of the Bourgeoisie (Le charme discret de la bourgeoisie, 1972) |
| Billy Wilder | Some Like It Hot (1959) |

## Ways to make your own movie diary

Coding is one way to write your own Movie Diary.
Example (in Python):

```
movies = []
movie_number = 0

while True:
    print("1. Add Movie")
    print("2. Show Movies")
    print("3. Show Your Movie Number")
    print("4. Exit")
    choice = input("Choose an option: ")  
    if choice == '1':
        new_movie = input()
        movies.append(new_movie)
        movie_number += 1
    elif choice == '2':
        print(movies)
    elif choice == '3':
        print(movie_number)
    elif choice == '4':
        print("Goodbye")
        break
    else:
        print("Please try again.")
```

### Links etc.

[My favorite film canon](https://1001films.fandom.com/wiki/The_List)
