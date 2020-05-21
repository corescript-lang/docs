# The Official Corescript Documentation
Corescript is a bare-bones minimalist computer language designed  
to be a jump-start for people getting into computer programming.

Corescript is not a production language. It is a learning tool.  
You can write advanced things in Corescript by pushing it to it's  
limits, and we encourage you to do so, but not seriously.

## Hello World Example
To start off, let's look at something very simple.  
This is the classic "Hello, World" program.
```
print Hello, World!
```

Pretty straightforward, right? Good, let's move on to the next example.

## Variables
Variables can simply be declared by using:
```
var name = John
```

You *must* use a space between the equal sign, or the code will  
not parse. And besides, it is easier to read that way.

To set a variable, use the `set` command.
```
set name = John Doe
```

## Printing Variables
Now that we have our cool variable, what do we do with it?  
Well, you can't eat it, nor can you use it to visit Mars, so  
let's try to print it to the screen.
```
print Hello, (name)!
```

In Corescript, anything between parenthesis will try to be parsed.  
If the parsing does not succeed, then it will be left alone, unparsed.

Now that we have a few basic commands down, let's use them to make another  
example.
```
input name = What's your name?
print Hello, (name)!
```

This will ask for input, and greet the user once they have done so.

# Labels + Goto
Sometimes you want to do something over and over again, like  
annoying somebody until they give in. We do this in programming too.  
```
:top
print This is repeated forever
goto top
```

In that example, we declare a label by using a `:` and putting  
our label text after it. Then we put in our code, and when finished, tell it  
to `goto` to the place where `:top` was called, and thus the cycle continues.

*In the web editor, type "slow" into the terminal to turn on slowmode. This
will allow recursive thingies to work without crashing your page.*




# Math functions
In programming, you will at one point need to use math.  
Whether it is adding +1, or calculating the chances you will win  
the lottery, programming would be useless without it.
