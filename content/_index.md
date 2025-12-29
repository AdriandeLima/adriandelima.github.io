---
title: "Home page blurb"
description: "The text that will show on the home page of the website"
preview: /assets/house.webp
---

{{< lead >}}

Adrian de Lima is a UK-based violinist and composer, specializing in classical performance, electronic composition, and sound design.

{{< /lead >}}

<div class="flex gap-4 justify-center">
<!-- FM:Snippet:Start data:{"id":"Button","fields":[{"name":"URL","value":"/categories/mywork"},{"name":"icon","value":""},{"name":"text","value":"My work"}]} -->
{{< button href="/categories/" target="_self" >}}
 My work
{{< /button >}}
<!-- FM:Snippet:End -->



<!-- FM:Snippet:Start data:{"id":"Button","fields":[{"name":"URL","value":""},{"name":"icon","value":"mail"},{"name":"text","value":"Contact"}]} -->
{{< button href="/contact/" target="_self" >}}
{{< icon "email" >}} Contact
{{< /button >}}
<!-- FM:Snippet:End -->

</div>

{{< list limit=3 >}}
<!-- TODO:
       
        fix lack of footer, 
        fix recents not displaying, 
        fix show more not showing, 
        fix favicons not showing
      
      
        Rewrite articles
        My work page
        Aboutme layout (card)
        larger buttons?
        Logo icon
        background image
       
