## Can you copyright a program you have made from scratch?

- posted by: [DonyorM](https://stackexchange.com/users/3223020/donyorm) on 2014-09-27
- tagged: `intellectual-property`, `software`, `copyright`
- score: 7

I'm programming a program in the Java programming language, I'm using no libraries other than the Java SDK, and I want to eventually sell the program.

Can I copyright this program so that no one else can legally distribute it without my permission?


## Answer 826

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-09-27
- score: 9

Well, yes. But I'm not sure that's what you're looking for.

A copyright is protection on artwork. Code, yes, is artwork, and it receives an immediate copyright (although you can also, of course, register that for more protection). That gives you protection from people stealing your source code (verbatim) and using it without your permission. Aside from the licensing, that's very useful in open source, where publishers are willingly sharing their source but still want some control over its use.

But that said, a copyright isn't really all that useful in a lot of cases.

Since this is about code, let's talk code. I'm a C# guy and know relatively little Java, but I imagine you can understand this. Let's loop through an array.

    int[] arr = new int[10];

    foreach (int v in arr)
    {
        Console.WriteLine(v);
    }

I now have (aside from the Stack Exchange license, which I believe puts all this under Creative Commons) a copyright on that code. Now, you come along, and want to use this algorithm, but you don't want to pay me usage fees. Fortunately for you, we use a multifaceted language. You use the following code in your application.

    int[] arr = new int[10];

    for (int index = 0; index < arr.Length; index++)
    {
        Console.Write(arr[index]);
        Console.Write(Environment.NewLine);
    }

Now, woah. You're doing exactly the same thing as me. But sadly, I have no claim over your code. You do it in a different way, so my copyright is irrelevant.

In laymen's terms, the difference here is similar to if I drew a green circle and you drew a red square, they're completely different.

All that aside, there's still some hope. They're still hotly debated, but software patents are possible. They're more expensive (it's not unreasonable to expect $20,000 over the lifetime of a patent, and a copyright is probably less than $100 unless you get into litigation), but they do give you more protection.

In our above example, I would want to get a patent on a method that prints out the contents of an array. Suddenly, both approaches are covered and you're out of luck.

Moving back out from this example, you can benefit from both of these forms of protection. Copyrights will, by default, protect your code if you choose to share it. On top of that, if you have any proprietary algorithms in your code (and there's a relatively good chance that you do), you could get those patented. You could also think about patenting the overall workflow or process of your application.

Your best option is to speak with a patent professional (with whom it won't be a public disclosure) about what your application does, and what might be protectable and protection-worthy in it.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
