---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page

title: Contact
parmalink: /contact

---

<div class="contact-info" style=" display: flex; align-items: text-align: center; center; gap: 20px; ">
<p class="phone-num" style=" font-size: x-large; ">
Phone Number: 816-299-1293
</p>

<p class="email" style=" font-size: x-large; ">
Email: bry.jimenex@gmail.com
</p>
</div>

<div style=" text-align: center; ">
<a href="https://www.linkedin.com/in/bryan-jim/" style=" font-size: xx-large;  "> LinkedIn  </a>
</div>


<form action="https://formspree.io/f/xpwjvepk" method="POST" 
      style="max-width:500px; margin:2rem auto;  padding:1.5rem; 
             border:1px solid #A5AEB2; border-radius:10px; 
             background:#black; font-family:Arial,sans-serif;
             ">

  <label style="display:block; margin-bottom:1rem; font-weight:600;color:#111;">
    Your Name
    <input type="text" name="name" required 
           style="width:100%; padding:.6rem; margin-top:.4rem;
                  border:1px solid #ccc; border-radius:6px; font-size:1rem;">
  </label>

  <label style="display:block;margin-bottom:1rem;font-weight:600;color:#111;">
    Your Email
    <input type="email" name="email" required 
           style="width:100%;padding:.6rem; margin-top:.4rem; 
                  border:1px solid #ccc;border-radius:6px;font-size:1rem;">
  </label>

  <label style="display:block;margin-bottom:1rem;font-weight:600;color:#111;">
    Message
    <textarea name="message" rows="5" required 
              style="width:100%;padding:.6rem;margin-top:.4rem;
                     border:1px solid #ccc;border-radius:6px;
                     font-size:1rem;resize:vertical;"></textarea>
  </label>

  <button type="submit" 
          style="padding:.75rem 1.25rem; background:#white; color:#black;
                 border:none; border-radius:6px; cursor:pointer;
                 font-size:1rem; font-weight:600;
                 transition:background .2s;">
    Send
  </button>
</form>




