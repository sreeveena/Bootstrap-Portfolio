# Bootstrap-Portfolio
Bootstrap Assignment
Bootstrap-Portfolio
Technologies used:
HTML
CSS
BOOTSTRAP

This assignment has three HTML pages :
1. About
2. Portfolio
3. contact
All the above pages has Links,content and footer which are common. The main difference in the above pages are in content block.
In above pages the header block has links to the other pages(content,about and footer)
'''
<header class="d-flex bg-white">
    <div class="nav  justify-content-end align-center mx-auto">
        <div class="name  bg-info ml-5 p-3 text-center  mr-auto p-3 mt-2">
            <a href="index.html" id="logo" class="text-white ">Sreeveena</a>
        </div>
        <div class= "nav-link  ml-5 mt-2">
            <a href="index.html" class="text-secondary text-center ">About</a>
        </div> 
        <div class= "nav-link mt-2">
            <a href="portfolio.html" class="text-secondary border border-secondary border-top-0 border-bottom-0 text-center pl-3 pr-4 ">Portfolio</a>
        </div>
        <div class= "nav-link  mt-2">
            <a href="contact.html" class="text-secondary text-center"> Contact</a>
        </div>
    </div>  
</header>
'''
In above pages the sticky footer block has the following code
'''
<footer class="page-footer bg-dark fixed-bottom mt-5">
    <div class="footer-copyright bg-info" style="height:5px">
    </div>
    <div class="footer-copyright text-center py-3">Copyright &copy
    </div>
</footer>
'''
The content block has modification in every page.
- About page has paragraph and image. they have been arranged in a page using float.
- Contact page has <form> and <lable> .
- Portfolio page has images and description specific to the image and description is positioned absolute to the image.

screenshot of the pages
About

![image](https://user-images.githubusercontent.com/7834767/66249362-e75cdc80-e6e6-11e9-94b3-317a77563118.png)

Contact

![image](https://user-images.githubusercontent.com/7834767/66249337-8503dc00-e6e6-11e9-8043-87e5f61822b7.png)

Portfolio

![image](https://user-images.githubusercontent.com/7834767/66249376-1e32f280-e6e7-11e9-8c15-c26e6525183e.png)