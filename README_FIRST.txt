/* By the power of Grey-Skull */

Ease of use for code-reviewer, enjoy! ;-)

What to un-comment and wherein styles.css;
(my unsolicited advice is open dev-tools and go to coverage, then delete the line items from there.. its faster)


1) line 3:
    what: <div>
    why: red border line to make element review easier.
    note: *the single pixel border will offset the design, uncheck for true page dimensions.

2) line 7: 
    what: <section>
    why: blue border line to make element review easier.
    note: *the single pixel border will offset the design, uncheck for true page dimensions.

3) line 261:
    what: .divider <background-color>
    why: "Yellow" was used to help in element design and review.
    note: background-color for this element was for ease of design (style nested or parent elements instead). 

4) line 269:
    what: .block-left <background-color>
    why: "Purple" was used to help in element design and review.
    note: background-color for this element was for ease of design (style parent element instead). 

5) line 410:
    what: #seciton2 <background-color>
    why: #9dc20b was used to help in element design and review.
    note: each individual #section? has a background-color for modularity/color control purposes. 

6) line 573:
    what: #seciton3 <background-color>
    why: #9dc20b was used to help in element design and review.
    note: each individual #section? has a background-color for modularity/color control purposes. 

7) line 612:
    what: #seciton4 <background-color>
    why: #9dc20b was used to help in element design and review.
    note: each individual #section? has a background-color for modularity/color control purposes. 


/* Additional/Special Features */

Everything has been laid out to fit "all" form factors (sized above 320px). 

The design was tested (latest builds) in Chrome, Edge, Firefox and Opera. 
*Note, Edge experiences an issue with the layout of #section3 but it looks fine so I left it.  


1) #section1:
    a) used css to "crop" and "inverse" banner-image provided. (I encourage you to open the image in a new tab) 
    b) positioned banner-image in an alternate fashion
    c) positioned block-right ("Learn Something...") such that it is floating on the banner-image
    d) animated block-right with a slide-in animation
    e) made "Start Here" a clickable button
    f) kept the content of block-left below 600px
    g) styled the "Read more" elements as buttons

2) #section2:
    a) kept the contnet of block-left below 600px 
    b) made "Read more" a clickable button (with the heaviest border-radius)
    c) *did not include block-right grey coloring to keep it the element unique (this is done in section3)

3) #section3:
    a) .features desktop-only has 3 child blocks (left,center, right-block) for modularity
    b) the above child elements (left, center, right-block) have two .feature per block for further modularity.
    c) the text was centered in the above elements to differ in styling from other #section?'s
    d) below 600px I added a collapsible element instead of simple divs or spans... enjoy ;-)

3) #section4:
    a) .block-right (only visible above 600px) has a :hover psuedo which turns the spans grey. 


/* Cliff Notes */

1) I could have tweaked the spacing in some places. 

2) I could have cleaned up the CSS file (I have things in the wrong place and some redundancy...) time is my issue.

3) I have yet to add accessibility (i didn't even add alts to my images... sorry). Will fix when not swamped. 

4) As a Graphic & Digital artist I could have added a color scheme but I wanted it to be an easy to review.

5) I have made more than my share of favicons... the black favicon is killing me... bucket list. 