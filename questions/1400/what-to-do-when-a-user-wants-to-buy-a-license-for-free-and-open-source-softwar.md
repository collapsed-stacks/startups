## What to do when a user wants to "buy a license" for free and open source software?

- posted by: [Nick Bolton](https://stackexchange.com/users/20131/nick-bolton) on 2014-11-17
- tagged: `business-model`, `sales`
- score: 9

Free and open source software can be *freely* redistributed with or without changes *and* with or without a price-tag. As a developer, I am free to sell open source software, which I do.

However, this creates an interesting scenario. Large corporate customers are used to asking software distributors questions like *"Do you offer a site license?"* -- well, this is tricky, technically, we're not selling a license here, we're selling the binaries. It is not possible to sell a license for the software, since its already licensed under the GPL.

So what do you tell a customer when they want to buy a license? <br />
*"Yeah sure, here's a quote."* or *"You're actually buying the binaries, here's a quote for that."*

 The first one is easier for the customer (they're just doing their job) and the second is perhaps more ethical (but confuses the customer).

Technically, I suppose you can impose a "**license**" to access the download page and support services -- this seems like the most sensible business strategy. Should you try to educate the user on rights, or just leave them to it? Because they probably don't care.


## Answer 1411

- posted by: [haneefmubarak](https://stackexchange.com/users/2619869/haneefmubarak) on 2014-11-18
- score: 1

For FOSS with extremely permissive licenses, such as MIT or BSD, you can suggest purchasing a support plan instead. Notify them that they are free to try and use the software indefintiely for free, although they will strongly benefit from purchasing support.

If the software is some sort of middleware or backend, suggest that you are also available for specialized consulting to help integrate the software with some of their existing tools or workflow.

You can also offer a possibly closed source version to them, where you can add specific custom features that they would like.

---

If the software is under a more restrictive license, such as GPL or AGPL, there usually isn't much you can do other than the above. However, if your CLA (contributors licensing agreement) automatically reassigns all copyright to you, then you can do more:

You can offer an enterprise version, with specific redistribution and/or usage terms, tailored to an agreement that you and your client agree on. This could include additional features or allow them to redistribute your package as part of an offering of their own, under their own licenses, with them paying you royalties on sales of such packages.

---

If all you wish to sell are the binaries, you can inform them that while they are free to build the software from source, you provide precompiled binaries that are available for purchase, along with support for said binaries.

Explain to them that you sell individual copies of the binaries, for use on individual machines, although if they would like to install the binaries across all of the machines on their site, you can come to an arrangement.

This gives them what they want while also being ethical and explaining their options to them. Often, they won't want the hassle of compiling binaries themselves and they would also like support, so it will still be in their best interests for them to purchase your binaries along with support.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
