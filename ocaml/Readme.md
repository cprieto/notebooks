# Learning OCaml

I had been through the book [Learning OCaml from the very beginning](http://ocaml-book.com/) and doing the exercises and some notes.

This is the result of my journey through this ML language.

By the way, I just finished reading the book and I cannot recommend the book _at all_. The book only touch the most basic things from the language, it is like studying C# learning the keywords. The examples and exercises are boring as hell and _absolutely all of them_ are plagued with curved balls and lists (seriously, after the chapter 4 you are so bored and it is so hard to finish the book because that). I did finish the book but I stopped doing the exercises after chapter 12 or so. The book doesn't explain a lot of things, in fact, the example code is not code an OCaml programmer will write (recursive functions without tail calls? please!) and depends on exercises for you to figure out.

Go and spent your money in [Real World OCaml](https://www.amazon.com/Real-World-OCaml-Functional-programming/dp/144932391X) or [Practical OCaml](https://www.amazon.com/Practical-OCaml-Joshua-Smith-2006-10-19/dp/B01JXSAIEM/), the later is an old book but it has realy good examples.

If you still interested in OCaml, check the `real_world_ocaml` directory.

I used [Jupyter OCaml](https://github.com/akabe/ocaml-jupyter) as a kernel for OCaml in Jupyter, you can go and install it yourself or use the [Docker image for IOCaml](https://hub.docker.com/r/akabe/iocaml/), I recommend this last one, specially since this is just a beginner book yet.

You can access it with:

```
docker run -p 8888:8888 --rm -v <notebooks>:/notebooks akabe/iocaml
```

Where `<notebooks>` is the directory where you put the download (or cloned) notebooks.
