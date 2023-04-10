# Markdown Demo
## This is a Markdown Demo.
### Using lots of headings...
#### some small,
##### some smaller,
###### and even some in different colors.

*written by Andrew Herold, [@heroldev](https://github.com/heroldev/) on GitHub ([profile README.md](https://github.com/heroldev/heroldev/blob/main/README.md))*

* [some things I still don't understand](https://github.com/heroldev/CS-302-hw4/blob/main/ThingsIDontUnderstand.md)

With that out of the way, let's begin...

Markdown
: **Markdown** is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.[^1]

Now we've moved into the classic body text. This is where most of your magic happens. In Markdown files, usually you'll have:
* Some bullet points explaining what you (the reader) is looking at
  * This clarifies the above bullet point!
    * This further clarifies the above bullet point
      * We can go...
        * as deep as we need.
          * Deeper than even the Mariana Trench!
- Also other bullet point types (using a hyphen instead of an asterisk)

But generally speaking, you'll have:
1. A clear, concise title.
2. An even more concise subheading (or a few).
3. Any amount of body text or other features to explain your repository.

Moving on..

---

See what I did there? That's a line break. Use it to **s p a c e** out your thoughts and spice up your document.

That's right! Markdown supports classic type styles like **bold**, *italics*, and even ***bold italics***. You can even use HTML syntax to <u>underline</u> and do other cool styles (within reason)! 

But you can't strikethrough, can you? ~~No, you can't~~ Yes you can! You can also ==highlight important text== and do ~subscript~ and ^superscript^.

Got some commands or code to show? You can do single line code formatting: `cat MarkdownDemo.md`

or even multi-line formatting
```
// cool, funky code goes here!
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the f***? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

You can also even have Wikitext-like tables! HTML tags work too.
| My | Table |
| ----------- | ----------- |
| Is | Better |
| Than | Yours |

---
Now, you might be wondering.. how do I join in on the fun? 
### Making a Markdown File
- [x] Open your editor of choice
- [ ] Create a file with a `.md` file extension
- [ ] Fill it with Lorem Ipsum (or whatever text you want)
- [ ] Save it (and commit it to your repository!)

Ideally, your fellow developers will say:
> LGTM! :rocket:

and hopefully not:

![a meme where someone approves a pull request with a comment saying "I ain't reading all that, I'm happy for you tho, or sorry that happened"](https://raw.githubusercontent.com/CS302spr23/hw-4-heroldev/main/meme.PNG)




[^1]: https://daringfireball.net/projects/markdown/syntax#philosophy
