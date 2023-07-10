# TESTING


## Compatibilit

To confirm correct functionality, responsiveness and appearance:
- The site has been tested on the following browsers: Chrome, Safari, Firefox.

    - Chrome :

    ![chrome browser](./readme_images/chrome.png)

    - Safari :

    ![safari browser](./readme_images/safari.png)

    - Firefox :
    ![firefox browser](./readme_images/firefox.png)

    ## Responsiveness

    - The site has been tested using the devtools that are implemented in Chrome browsers.
        #### Main page
        - Desktop screens:
        ![large screen](./readme_images/desktop-mainpage.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-mainpage.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-mainpage.png)

        #### Cast page
        - Desktop screens:
        ![large screen](./readme_images/desktop-cast.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-cast.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-cast.png)

       #### Awards page
        - Desktop screens:
        ![large screen](./readme_images/desktop-awardpage.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-awardpage.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-awardpage.png)
 
      #### About page

       - Desktop screens:
       ![large screen](./readme_images/desktop-aboutpage.png)

       - Tablet screens:
       ![tablet screen](./readme_images/tablet-aboutpage.png)

       - Mobile screens:
       ![Mobile screen](./readme_images/mobile-aboutpage.png)

          #### Quote section
        - Desktop screens:
        ![large screen](./readme_images/desktop-quotesection.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-quotesection.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-quotesection.png) 

           #### Review page
        - Desktop screens:
        ![large screen](./readme_images/desktop-reviewpage.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-reviewpage.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-reviewpage.png)


        #### Response page
        - Desktop screens:
        ![large screen](./readme_images/desktop-responsepage.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-responsepage.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-resposepage.png)




           #### Footer
        - Desktop screens:
        ![large screen](./readme_images/desktop-footer.png)

        - Tablet screens:
        ![tablet screen](./readme_images/tablet-footer.png)

        - Mobile screens:
        ![Mobile screen](./readme_images/mobile-footer.png)


## Manual testing

| Feature | Action | Expected Result | Tested | Passed | Comments |
| --- | --- | --- | --- | --- | --- |
 Header | | | | |  
| Logo | Click on the "Logo" | The user is redirected to the main page | Yes| Yes | - |
 Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Cast | Click on the "Cast" link | The user is redirected to the cast page | Yes | Yes | - |
| Awards | Click on the "Awards" link | The user is redirected to the awards page | Yes | Yes | - |
| About | Click on the "About" link | The user is redirected to the about page | Yes | Yes | - |
| Review | Click on the "Review" link | The user is redirected to the review page | Yes | Yes | - |
Cast page | | | | | |
| cast image | User hover the image | Image zoom on mouseover | Yes | Yes | - |
Awards page | | | | | |
| award image | User hover the image | Image zoom on mouseover | Yes | Yes | - |
Review page | | | | | |
| Name input | Enter the name | The name is entered | Yes | Yes | If user doesn't enter the name, the error message appears |
| Email input | Enter the email | The name is entered | Yes | Yes | If user doesn't enter the name, the error message appears |
| Review textarea | Enter the review | The review is entered | Yes | Yes | If user doesn't enter the review,the error message appears. |
| Rating radio button | Click on the radio button | The radio button is selected | Yes | Yes | Once a radio group has been created, selecting any radio button in that group automatically deselects any radio button currently selected in the same group. |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |
| Return to home page | click on the "Return to home page" link| The user is redirected to the home page | Yes | Yes | - |
| Footer | | | | | |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |

# Validator testing
 ### HTML
  ##### Home Page
  - No errors or warnings were found when it was run through the official W3C validator.
    - ![home page html validator](./readme_images/homepage-htmlvldtr.png)
##### Response page
-  No errors or warnings were found when it was run through the official W3C validator.
    - ![response page html validator](./readme_images/responsepage-htmlvldtr.png)

### CSS
- No errors were found in the official W3C (Jigsaw) check.
    -![css validator](./readme_images/cssvalidator.png)
- 2 warnings were found
    - ![css validator warning](./readme_images/csswarning.png)
     - imported style sheets are not checked
     - The @-moz-document rule is specific to Mozilla Firefox and is not a standard CSS rule recognised by the W3C (World Wide Web Consortium).
    - The @-moz-document rule is a vendor-specific extension provided by Mozilla to target specific rules in Firefox only. It allows you to apply styles or rules specifically for Firefox browsers.

## LightHouse report
- With the help of Lighthouse in devtools, I have been able to confirm that the website functions well, is accessible and that the colours and fonts chosen are readable
    ### Home page

  ![home page lighthouse](./readme_images/lighthouse-homepage.png)

   ### Response page

  ![response page lighthouse](./readme_images/lighthouse-responsepage.png)

## Bugs
### Solved bugs
1.  First I used image logo crop from an image but its not clear all screens.
*Solution:* I created new logo using figma

1. Cast image did not fit border because all images are different width and height, so I made height and width same size, looks unclear and not properly aligned.
*Solution:* Object fit and Object position property used to fix the problem.

1. Cards on awards page did not fit on mobile screen 
*Solution:* In the media query i changed flex value to 50%.
### Unsolved bugs
- There is a problem in the About page, the paragraphs show some gaps on the mobile screen.
 ### Mistakes
- Mistakes were made while committig,I did some spelling mistakes.
- Also some committs are not properly committed.
