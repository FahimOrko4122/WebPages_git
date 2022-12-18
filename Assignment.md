
## Exercise 01

* ### italic (_) (xyz _**xyz**_) and bold (**) (**xyz**)
    1. Writing in Markdown is _not_ that hard!
    2. I **will** complete these lessons!
    3. _"Of course,"_ she whispered. Then, she shouted: "All I need is **a little moxie!**"
    4. If you're thinking to yourself, _**This is unbelievable**_, you'd probably be right.

* ### Header (#)
    1.  ans -
        * # Header one
        * ## Header two
        * ### Header three
        * #### Header four
        * ##### Header five
        * ###### Header six
    
    2. ans - 
        * #### Colombian Symbolism in _One Hundred Years of Solitude_

        * Here's some words about the book _One Hundred Years..._.


* ### Links [linkname] (linkadess) - (For acatual link no gaps between name and adress)

    1. [Search for it.](www.google.com)
    2. [You're **really, really** going to want to see this.](www.dailykitten.com)
    3. #### The Latest News from [the BBC](www.bbc.com/news)
    4. 
        * Do you want to [see something fun][a fun place]?

        * Well, do I have [the website for you][another fun place]!

        [a fun place]: www.zombo.com
        [another fun place]: www.stumbleupon.com

* ### Images
    1.  #### Image of Tiger
        ![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

    
    2.  #### Cats 
        ![Black cat][Black]

        ![Orange cat][Orange]

        [Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
        [Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

* ### BlockQoutes

    1. I read this interesting quote the other day:

        > "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

    2. 
        >Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
        >
        >His father told him that story: his father looked at him through a glass: he had a hairy face.
        >
        >He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.
    
    3. >He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

* ### Lists
    1. 
        * Flour
        * Cheese
        * Tomatoes

    2. 
        1. Cut the cheese
        2. Slice the tomatoes
        3. Rub the tomatoes in flour

    3.
        * Azalea (_Ericaceae Rhododendron_)
        * Chrysanthemum (_Anthemideae Chrysanthemum_)
        * Dahlia (_Coreopsideae Dahlia_)
  
    4.
        * Calculus
            * A professor
            * Has no hair
            * Often wears green
        * Castafiore
            * An opera singer
            * Has white hair
            * Is possibly mentally unwell

    5. 
        1. Cut the cheese

            Make sure that the cheese is cut into little triangles.

        2. Slice the tomatoes        
        
            Be careful when holding the knife.
        
            For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

* ### Paragraphs

    1.    
        We pictured the meek mild creatures where
        They dwelt in their strawy pen,  
        Nor did it occur to one of us there  
        To doubt they were kneeling then.  
    
    2. 
        1. Crack three eggs over a bowl.  
        Now, you're going to want to crack the eggs in such a way   that you don't make a mess.    
        If you _do_ make a mess, use a towel to clean it up!    
        2. Pour a gallon of milk into the bowl.    
        Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

## Exercise 02

* #### XHTML - 
    _**Extensible HyperText Markup Language (XHTML)** is part of the family of XML markup languages. It mirrors or extends versions of the widely used HyperText Markup Language (HTML), the language in which Web pages are formulated.
    While HTML, prior to HTML5, was defined as an application of Standard Generalized Markup Language (SGML), a flexible markup language framework, XHTML is an application of XML, a more restrictive subset of SGML. XHTML documents are well-formed and may therefore be parsed using standard XML parsers, unlike HTML, which requires a lenient HTML-specific parser._

* #### SGML - 
    _**SGML (Standard Generalized Markup Language)** is a standard for how to specify a document markup language or tag set. Such a specification is itself a document type definition (DTD). SGML is not in itself a document language, but a description of how to specify one. It is metadata.
    SGML is based on the idea that documents have structural and other semantic elements that can be described without reference to how such elements should be displayed. The actual display of such a document may vary, depending on the output medium and style preferences_


## Exercise 03

* **Click here**
[![IMAGE ALT TEXT HERE](https://www.howtogeek.com/wp-content/uploads/2021/08/YouTube-logo-hero-1.png?width=398&trim=1,1&bg-color=000&pad=1,1)](https://www.youtube.com/watch?v=xvFZjo5PgG0)


* **The way of the wolf**
![A pack of wolfs](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR387bijKH-ZBdo1ekzE495kSqmXk2BGBjgxQ&usqp=CAU)


## Exercise 04
```csharp
    public class Person

    {
    
        private string name;
        private int age;

        public Person(string initialName)
        
        {
            
            this.age = 0;
            this.name = initialName;
        
        }
    
        public void PrintPerson()
    
        {
        
            Console.WriteLine(this.name + ", age " + this.age + "years");

        }

        public void GrowOlder()
    
        {

            this.age = this.age + 1;

        }

    }
```
