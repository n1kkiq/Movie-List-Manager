# Movie-List-Manager(Python only no tkinter)
Create a list of movies your willing to watch or have already watched

movie=[]
while True:
    print("1. add movie")
    print("2. show movie")
    choice=input("enter: ")

    if choice == 1:
       name = inputer("movie nane :")
       movies.append(name)
    elif choice ==2:
       for m in movies:
            print m
