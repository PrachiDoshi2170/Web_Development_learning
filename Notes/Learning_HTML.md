**Q. What happens in the backend when you enter www.google.com?** <br>
Ans. So what happens is the client browser takes in the input sends it to the internet service provider abbreviated as ISP &#8594 The ISP then performs few functions before contacting DNS server. 1) First it checks whether you have access to the internet service or not, if you do it check the local cache to find whether it has IP of the website available, 2) If not its checks the set of IP addresses that are added to blocked and dnager list 3) If neihter of the above steps return an answer it sends the request to the local DNS Server. &#8549 The local DNS server than locates and finds the corresponding IP address to the given website and if it is not able to find IP addresses , it approaches Global DNS Servers to perform the same function. &#8549 Once the corresponding IP address is found the DNS Server contacts back the Internet Service Provider with the details. &#8549 Now the ISP provides these details to the client's browser and loads website.

**HTTP is an abbreviation for Hypertext Markup Language**
Hypertext means the combinations of text that can link to other piece of text. Keeping that concept in mind the word hypertext was used as one page is connected to another part through links embedded in the text.
Markup Language means that the part that needs to be shown in the website will be enclosed between some kind of language/tags that help the browser to interpret what that part of the website needs to be rendered as.

In HTML, anything in the angular brackets is called a tag. For eg: `<h1> Hello World </h1>`. The h1 inside the angualar bracket are called tags, while the whole line is called one element.

**Q. What is the purpose of the heading element?** <br>
The heading tag allows to segregate and showcase the topic into differernt heading levels. It looks similar to the one given below.
<h1> Heading 1 </h1>
  <h2> Heading 2 </h2>
    <h3> Heading 3 </h3>
      <h4> Heading 4 </h4>
        <h5> Heading 5 </h5>
          <h6> Heading 6 </h6>

          

> Note: Make sure there are no more than 1 `<h1>` element and make sure you do not skip the heading level.
> For more reference to the various html tags and interactive examples on the same, visit [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)

**Q. What is the purpose of the paragraph element?** <br>
Ans. The main aim of the `<p></p>` tag is to segregate the normal text on the website into different lines or paragraphs to enhance the readabiity of the text and content on the website. 

**Q. What are self-closing tags?**<br>
Ans. Some tags similar to `<hr/>` tag called the horizontal rule tag that adds a horizontal line between two elements. These tags are sef closing of the nature becuse you are not supposed to add ay kind of content there, no image, text, video etc. and hence they do not want to take up space by making them as two differernt tags that do not contain anything in between them. Hence they are merged into one. Apart from   `<hr/>` tag, there are many other self-closing tags such as `<br/>` (break element)

> Note: Make sure anytime you are using a `<br />` tag, if the lines you are separating are a part of the single paragraph make sure to first add the paragraph tag and then separae lines within the paragraph. This is generally termed as a good practice for readablity and accesibility when you are working with other developers. Hence keep this in mind while writing a code.




 
