Notes from [WesBos' Mastering Markdown Course](http://masteringmarkdown.com/)

# Heading One

Heading One
==============

## Heading Two

Heading 2
------------

### Heading Three

There is no dash equivalent for heading three or lower... use hashes instead.

Bruce is _cool_.

I **love you**.

I _really_ love you.

Bruce is ~~really cool~~!

---

<http://www.github.com/bitbruce>

[My Github](http://www.github.com/bitbruce)

[My Github](http://www.github.com/bitbruce "This is currently just a redirect")

Check out [Bruce's][1] GitHub. Or find it [here][site].

[1]: http://www.github.com/bitbruce
[site]: http://www.github.com/bitbruce

---

> Block quote example
>
> - **Quote author**

---

![A picture example!!](https://is2-ssl.mzstatic.com/image/thumb/Purple118/v4/89/9f/77/899f771e-1e48-0db7-d31b-6abec6cb198a/AppIcon-1x_U007emarketing-0-85-220-0-8.png/1200x630bb.jpg "This is the tooltip")

## A shortcut example!
![Archery][pic]

[pic]: https://is2-ssl.mzstatic.com/image/thumb/Purple118/v4/89/9f/77/899f771e-1e48-0db7-d31b-6abec6cb198a/AppIcon-1x_U007emarketing-0-85-220-0-8.png/1200x630bb.jpg

---

+ item 1
+ item 2
+ item 3
- item 1
- item 2
- item 3

1. Items
    * subitem 1
        * subsubitem 1

            Not an item, just a paragraph

            ![](https://is2-ssl.mzstatic.com/image/thumb/Purple118/v4/89/9f/77/899f771e-1e48-0db7-d31b-6abec6cb198a/AppIcon-1x_U007emarketing-0-85-220-0-8.png/1200x630bb.jpg)
    * subitem 2
1. Automatically
1. Ordered

---

Here is my code:

    var x = 100;
    const bow = 'recurve';    

```javascript
var ammo = carbonfiber;
```

Hey did you try `var x = 1000;`?

```diff
var x = 100;
-var y = 200;
+var y = 300;
```

---

|Table header|Table header2|
|:-----------:|------------:|
|Abc|3|
|Def|5|
>There are also markdown table generators

---

### GitHub treats

* [x] Get Milk
* [ ] Crack Eggs
* [ ] Use these in pull requests too

Use hashtag for issue tracking, and @ symbol to mention people
