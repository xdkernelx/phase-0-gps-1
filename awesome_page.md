
#Awesome things

__DBC__ is awesome.

__Coffee__ is awesome.


*We are working on a GPS for DBC!*

    #!/usr/local/bin/python3
    # Nestor Alvarez
    # helpers.py
    # Handles some routine CGI chores
    # 201607018

    def __main__():
        print("#" * 28,"\n", "Testing...1, 2, 3...testing!\n", "#" * 28, "\n", sep="")
        # code to test area() and circ()
        radius = 10
        print("A circle with a radius of {} has a circumference of {:.2f} \
    units and an area of {:.2f} square units.".format(radius, circ(radius), area(radius)))
        print(c2f(30))
        print(f2c(30))

    pi = 3.14159
    def area(r):
        ##area(r): return the area of a circle with radius r.
        global pi
        return(pi * r * r)

    def circ(r):
        global pi
        return(2 * pi * r)

    if __name__ == '__main__':
          __main__()



[http://devbootcamp.com](devbootcamp)

![alt text](http://puu.sh/q7DL0/cc8df7ec19.png "Tacticool")