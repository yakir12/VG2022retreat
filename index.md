---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

<style>
section::after {
  content: attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total);
}
</style>


![bg left:40% 80%](link.png)

# Webapp development for scientists

Yakir Gagnon - Lund Vision Group meeting 2024/09/04

<!--Admittedly this will not be equally useful to everyone here, but it proved very useful to me, so I'm hoping this might help others as well-->

---

# Why

You have *something* to *share with the world*

<!--
Why do we want to develop a webapp?
You've built "something" you'd like to "share with the world". 
The something could be a research paper, a new method you've developed, a tool you needed in your research, a proof of concept, anything really. 
You'd like others to see it, use it, contribute to it, and interact with it. You already know that this should prove useful to your colleagues, or students, but you need to first give it to them.
-->

---

# How

- Scripts with some instructions (e.g. `Matlab`, `Python`, `Julia`)
- Compiled executable, aka a program (e.g. `.exe`)
- Webapp

<!--
How do you give them the thing you've built?
There are mainly 3 channels:
- Scripts: by far the most common way. Riddled with problems:
    1. This will only work on the exact same system
    2. Recreating the exact same environment can be really hard
    3. Can require some niche technical skills
- Compiled executable: Awesome when it works:
    1. Very static, hard to update
    2. available only for a few platforms
    3. Can be hard to produce
- Webapp: Requires web development knowledge
-->

---

# [GenieBuilder](https://genieframework.com/#GB)

- Drag & drop, no-code UI builder
- Backend app logic in Julia
- Deploy to the world-wide web with one click

<!--
Allows you to take your (Julia) script, and with zero webdev knowledge turn it into a webapp.
-->

---

## Example

The Dacke-lab needed a table generator for celestial events that they can use in their field work

[SunMoonTables](https://7qme8.launch.juliahub.app/)

<!--
1. Let the user decide the dates they'll be in the field.
2. Which field station it is they are going to.
3.Do they want to include any crepuscular angles?
4. What sun elevations do they want to include?
5. and that's it!

Most of the functionality and code is in producing this table (calculating when the sun and moon will be at the crepuscular, horizon, and selected elevations for the desired dates and location).
The GUI and reactivity on the webapp is all taken care of by GenieBuilder.
-->

---

# Advantages

- Easy to update
- Works on all platforms
- Always accessible

<!--
- Easy to update, augment, and change: I can always change the code as I like, and redeploy
- Works on all platforms: who doesn't have a web-browser
- Always accessible: If you are online, you can access it
-->

---

# Disadvantages

- Costs a bit (depends on the usage)
- Applications with large input and/or output files

<!--
- Costs a bit: my app cost 100 sek last month
- Doesn't fit with applications with large input and/or output files: you'd need to upload and/or download the files which could be slow and inefficient compared to processing it locally on your machine.

So that's it! I think I'll try and go through this webapp route for anything that fits well with it in the future. Feel free to ask me if you have any questions about this thing, and thanks for listening!
-->
