# Fundamentals of Software Testing Course

👋 Welcome to the showcase of bug reports crafted during my manual testing course at QATestLab.

Throughout this course, I explored various testing concepts and methodologies, creating bug reports that demonstrate my understanding of each topic. 

Below is a summary of the key themes covered in each lecture:

* #### Lecture 1: Introduction. What is a bug (defect)?

This lecture delved into bug report design, covering attributes, tools for capturing screenshots, and tasks to define the core of a bug.

* #### Lecture 2: Web projects testing

Explored peculiarities of layout testing, checklists, and cross-browser testing.

* #### Lecture 3: Approaches to the Functional Testing

Discussed types of testing, functional testing, checklists for functional testing, testing web forms, testing techniques, and testing without requirements.

* #### Lecture 4: Software Testing Life Cycle

Explored the definition of a test plan, rules for its creation, testing, and development processes, and an introduction to Agile and Scrum methodologies.

* #### Lecture 5: Test design. Test cases

Focused on the definition of test cases and the stages of software testing.

* #### Lecture 6: Mobile testing

Explored the peculiarities of web app testing and tasks to define the core of bugs in the mobile testing context.

* #### Lecture 7: Game testing

Covered the peculiarities of game testing and tasks to define the core of bugs in the gaming domain.

## Bug Reports Showcase

In the following sections, you'll discover instances of my practical work, featuring bug reports aligned with the themes discussed in each lecture. Each bug report is a demonstration of how I applied the knowledge acquired during the course.

## Category: Homework-1

Task: Describe 3 bugs from the [video](https://www.dropbox.com/scl/fi/26bpxtzv2iczvoe2y1f5d/Slide-73-Video-with-bugs-for-homework.mp4?rlkey=dskhn0tj4g44avvzhuk2a4tuo&dl=0) in the Mantis bug tracking system.

---
### ID-1: One of the banners is not displayed in the banner section on the main page of the site.

**Description:** An empty area instead of the banner is displayed in the banner section on the main page of the site.

**Steps To Reproduce:** 
  1. Open the site - trainingcentre.wixsite.com/design.
  2. Pay attention to the banner section on the main page.

**Actual result:** One of the banners is not displayed in the banner section on the main page of the site.

**Expected result:** All banners are visible in the banner section on the main page of the site.

**Environment:** Google Chrome 87.0.4280.88 Windows 10 x64

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/ccv9xb98mpzj94saeuhj4/hw_1_1_banner_bug.png?rlkey=925acvprotgavrg6rufp9118u&dl=0)

---

### ID-2: The “404 Error Page Not Found” message is shown after clicking the “PROJECTS” menu.

**Description:** The “404 Error Page Not Found” message is shown on the “PROJECTS” page after clicking the “PROJECTS” menu.

**Steps To Reproduce:** 
  1. Open the site - trainingcentre.wixsite.com/design.
  2. Click the “PROJECTS” menu link.
  3. Pay attention to the error message.

**Actual result:** The “404 Error Page Not Found” message is shown after clicking the “PROJECTS” menu.

**Expected result:** The content of the page is shown after clicking the “PROJECTS” menu.

**Environment:** Google Chrome 87.0.4280.88 Windows 10 x64

**Attachments:** [View the demonstration of the issue in this video](https://dl.dropboxusercontent.com/scl/fi/e9anamlyt9s70ttngty0e/hw_1_2_404_error.mp4?rlkey=tzq6av4fc3euuxymabds8o33a&dl=0)

---
### ID-3: The main page is not scrolled to the top after clicking the “UP” button.

**Description:** The main page is not scrolled to the top after clicking the “UP” button.

**Steps To Reproduce:** 
  1. Open the site - trainingcentre.wixsite.com/design.
  2. Scroll down to the bottom of the page.
  3. Find the “UP” button in the right bottom corner.
  4. Click the “UP” button.
  5. Pay attention to the button response.

**Actual result:** The main page is not scrolled to the top after clicking the “UP” button.

**Expected result:** The main page is smoothly scrolled to the top after clicking the “UP” button.

**Environment:** Google Chrome 87.0.4280.88 Windows 10 x64

**Attachments:** [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/ih157541fn5tpq1b5c3r5/hw_1_3_up_button.mp4?rlkey=z0rvd0rktdwtbb1q95p8vy7lb&dl=0)

## Category: Homework-2

Task: Complete and pass the layout and cross-browser compatibility checklist of the [website](http://opencart.qatestlab.net/).

---
### ID-4: The email icon and content are misaligned to the right within the “Store Info” section in the site footer.

**Description:** The email icon and content are misaligned to the right within the “Store Info” section in the site footer.

**Steps To Reproduce:** 
  1. Go to the site: http://opencart.qatestlab.net/
  2. Scroll down to the site footer.
  3. Find the “Store Info” section.
  4. Pay attention to the email alignment.

**Actual result:** The email icon and content are misaligned to the right within the “Store Info” section in the site footer.

**Expected result:** All elements, including the email, are correctly aligned in a single vertical line within the “Store Info” section in the site footer.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/73dhdy2dkw2hkb064wl6l/hw2_bug_5_mod.png?rlkey=77j01x1pfj1o9wxq7qc2tphof&dl=0)

---
### ID-5: The image that does not correspond to its name is displayed in the "Aquariums" category within the “Special offers” block.

**Description:** The image that does not correspond to its name is displayed in the "Aquariums" category within the “Special offers” block after choosing the English site language.

**Steps To Reproduce:** 
  1. Visit the website http://opencart.qatestlab.net/
  2. Choose the English site language.
  3. Scroll down to the “Special offers” block.
  4. Pay attention to the "Aquariums" category.

**Actual result:** The image that does not correspond to its name is displayed in the "Aquariums" category within the “Special offers” block.

**Expected result:** The image that corresponds to its name is displayed in the "Aquariums" category within the “Special offers” block.  

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/15kmv1qslcs4ky159lfx5/hw2_bug_4.png?rlkey=fcpnz3j2mdxwiisrf3e7nx6jp&dl=0)

---
### ID-6: The "Lorem ipsum" placeholder text is displayed in the third banner block on the home page.

**Description:** The "Lorem ipsum dolor sit amet, consectetur adipiscing elit" placeholder text is displayed in the third banner block, which features a cat picture, on the home page.

**Steps To Reproduce:** 
  1. Visit the website http://opencart.qatestlab.net/
  2. Scroll down the page to find the third banner block.
  3. Examine the banner text on the left banner, which features a cat picture.

**Actual result:** The "Lorem ipsum" placeholder text is displayed in the third banner block on the home page.

**Expected result:** Accurate and meaningful text is displayed in the third banner block on the home page.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/igy2uip8en4ga7d6qds8o/hw2_bug_3.png?rlkey=1zvoz3ph53h8irbg852dgrtyb&dl=0)

---
### ID-7: The banners are misaligned in the first banner block on the home page.

**Description:** The banners are not aligned to a common horizontal baseline in the first banner block on the home page.

**Steps To Reproduce:** 
1. Visit the website http://opencart.qatestlab.net/
2. Locate the first banner block.
3. Pay attention to the bottom banner’s alignment.

**Actual result:** The banners are not aligned to a common horizontal baseline in the first banner block on the home page.

**Expected result:** The banners are aligned to a common horizontal baseline in the first banner block on the home page.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/smmjh9p09x5vuf0hj4yby/hw2_bug_2_mod.png?rlkey=zug2vnu2je42dlfw7zc7q13j3&dl=0)

---
### ID-8: Euro and Pound Sterling symbols are not encoded properly on the site header after opening the dropdown currencies menu.

**Description:** “Â‚¬” instead of “€” Euro symbol and “Â£” instead of “£” Pound Sterling symbol are displayed on the currency buttons in the header after opening the dropdown currency menu or changing currency.

**Steps To Reproduce:** 
  1. Visit the website http://opencart.qatestlab.net/
  2. Locate the currency menu in the upper right corner of the page.
  3. Click to open the currency dropdown menu.
  4. Observe the presentation of the Euro (€) and Pound Sterling (£) symbols.
     
**Actual result:** Euro and Pound Sterling symbols are not encoded properly on the site header after opening the dropdown currencies menu.

**Expected result:** Euro and Pound Sterling symbols are encoded as “€” and “£” on the site header after opening the dropdown currencies menu.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/f7m25suxls2m0d60evglc/hw2_bug_1_mod.png?rlkey=7o86y7ecwqnbgr5xlzrvatbsp&dl=0)

---
### ID-9: Articles are not related to the pet store website theme on the site blog.

**Description:** All articles are not related to the pet store website theme on the site blog. The bug is reproduced in both English and German languages on the site.

**Steps To Reproduce:** 
  1. Go to the site: http://opencart.qatestlab.net/
  2. Set the site language to English (German).
  3. Scroll down to the site footer.
  4. Click the “Blog” link in the “Information” section.
  5. Pay attention to the irrelevance of articles to the website theme.

**Actual result:** Articles are not related to the pet store website theme on the site blog.

**Expected result:** Articles are related to the pet store website theme, such as content about pet care, products, and other topics of interest to pet owners on the site blog.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/wit3y9i51anpyvhxc5r7m/hw2_bug_7.png?rlkey=i7rj3flp66e5goh3u4jxjglwl&dl=0)

---
### ID-10: The placeholder is shown in the “Search” field after entering data.

**Description:** The placeholder is shown in the “Search” field after entering data.

**Steps To Reproduce:** 
  1. Go to the site: http://opencart.qatestlab.net/
  2. Find the “Search” field.
  3. Enter any data in the “Search” field.
  4. Pay attention to the presence of a placeholder.

**Actual result:** The placeholder is shown in the “Search” field after entering data.

**Expected result:** The placeholder is not shown in the “Search” field after entering data.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/3hk81e1rdsvlafavvtwww/hw2_bug_8.png?rlkey=4380uwyn5rci696sry4lz1d6h&dl=0)

---
### ID-11: The error message is displayed after clicking on the Twitter social media icon when the site language is set to English.

**Description:** The "Hmm...this page doesn't exist. Try searching for something else." error message is displayed on the browser tab after clicking on the Twitter social media icon when the site language is set to English.

**Steps To Reproduce:** 
  1. Go to the site: http://opencart.qatestlab.net/
  2. Choose the English site language.
  3. Scroll down to the social media links block in the footer.
  4. Click the Twitter icon.
  5. Pay attention to the error message.

**Actual result:** The error message is displayed after clicking on the Twitter social media icon when the site language is set to English.

**Expected result:** The Twitter social media page is displayed after clicking on the Twitter social media icon when the site language is set to English.

**Environment:** Firefox 118.0.2 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.89 (64-bit),
- Opera 104.0.4944.23.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/dap7gzni9bzbpjjzajexf/hw_2_bug_6_mod.mp4?rlkey=oaxx1tqjornck3jcfup83kviw&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/7b3j4g65co9do8r4t3tez/hw2_bug_6_1_mod.png?rlkey=l1lv1nkfo57qyarsyuuchyd3h&dl=0)

## Category: Homework-3

Task: Create bug reports (functional) in the Mantis bug tracker, found on the [test site](http://opencart.qatestlab.net/) on desktop devices.

---
### ID-12: The product that is not available in red is displayed in search results after applying the red color filter.

**Description:** The “Easipet Fabric Pet Carrier, Medium,Blue” product, which is not available in red, is displayed in search results after applying the red color filter.

**Steps To Reproduce:**
1. Open the site http://opencart.qatestlab.net/.
2. Log into the account using valid credentials.
3. Click the “Dogs” category in the navigation menu.
4. Apply the red color filter.
5. Open the “Easipet Fabric Pet Carrier, Medium,Blue” product.
6. Pay attention that the product is not available in red.

**Actual result:** The “Easipet Fabric Pet Carrier, Medium,Blue” product, which is not available in red, is displayed in search results after applying the red color filter.

**Expected result:** Only the products available in red color are displayed in the search results after applying the red color filter.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/fhkjp61yloydv1zl70scq/hw3_bug_3.mp4?rlkey=xnrkzw74kp1qpwy2fqlz4ngpo&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/4h2td58gfd0in6c9ynilt/hw_3_bug_3.png?rlkey=xj2maait1ujp0me4ahcu8udb0&dl=0)

---
### ID-13: The product quantity is not calculated correctly in the drop-down cart after adding the product to the cart.

**Description:** The two “Black Water Proofing Dog Boots” items are displayed in the drop-down cart after adding one item to the cart.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net/ and log into the account.
2. Click the “Dogs” category in the navigation menu.
3. Add the “Black Water Proofing Dog Boots Pet Shoes” product to the cart.
4. Choose the product size and color.
5. Click the “ADD TO CART” button.
6. Scroll up to the cart icon in the header.
7. Pay attention to the product quantity.

**Actual result:** The two “Black Water Proofing Dog Boots” items are displayed in the drop-down cart after adding one item to the cart.

**Expected result:** The one “Black Water Proofing Dog Boots” item is displayed in the drop-down cart after adding only one item to the cart.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

The bug is also relevant for the products in the “Dogs” category:
- HALO PET MICROCHIP SCANNER MID06(PINK in a Carry Case with Car Charger)
- HDP Dog Boots Blue Set of 4 Medium
- Hing Designs The Bone Bowl with Non Slip Rubber Feet and Dishwasher Safe Removable Stainless Steel Bowls, Pink
- LeopetÂ® HTBT10 75x60 Small Dog Bed 75x60x19 cm DIFFERENT COLOURS
- LeopetÂ® KBM001 2grau Cat Tree Scratching Post Kitten Climbing Exercise Activity Centre Sisal
- PetFusion Pet Food Mat in Premium FDA Grade Silicone (Large, Grey)
- Petown Soft sided Pet Carrier pet Carriers Airline Approved with Foldable and Washable (Gray)
- Silvercell-Pets-Puppy-Dogs-Clothes-Jacket-Little-Heart-Knit-Sweater-Coat-Pink-XL_1
- Dog & Puppy Toys
- Cat and Dog Toothbrush
- Dog Treats
- Luxurious Unique Beaded Collar
- Teething toy Blue
- TRIXIE 39813 Traveller Capri I Pet Carrier 48 cm

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/71uqj47uffpbc3jvl8uag/hw3_bug_2.mp4?rlkey=pbgt5kmg4rv2o9bcrbq7s694v&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/omli9f2e0owc0uw78fx9u/hw3_bug_2.png?rlkey=3gioneg5e8i4c1pfym1hyrx10&dl=0)

---
### ID-14: The success message is not displayed on the page after adding a product to the wish list from the drop-down cart.

**Description:** The success message is not displayed on the bottom notification area of the page after adding a product to the wish list from the drop-down cart.

**Steps To Reproduce:** 
1. Go to the site: http://opencart.qatestlab.net/
2. Log in using a valid credentials.
3. Scroll down to the “Bestsellers” section.
4. Add the “Dry Cat Food” product to the cart.
5. Click on the drop-down cart icon in the header.
6. Click the heart icon to add the “Dry Cat Food” product to the wish list.
7. Pay attention to the absence of a success message.

**Actual result:** The success message is not displayed on the bottom notification area of the page after adding a product to the wish list from the drop-down cart.

**Expected result:** The success message is displayed on the bottom notification area of the page after adding a product to the wish list from the drop-down cart.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/f3d5mr2h68tfnt4cdlck1/hw3_bug_1.mp4?rlkey=tv55gaxe8gkeaq0pyhagbso66&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/jtjld58frwjbiq88s6vrg/hw_3_bug_1.png?rlkey=b3aixxfhlswrhykq62zmz8uiw&dl=0)

---
### ID-15: The irrelevant message is displayed in the search results after there are no products matching the search criteria.

**Description:** The irrelevant "Your shopping cart is empty!" message is displayed in the search results after there are no products matching the search criteria.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net/.
2. Log into the account using valid credentials.
3. Click the “Small Pets” category in the navigation menu.
4. Apply a yellow filter with zero results.
5. Pay attention to the absence of relevant messages.

**Actual result:** The irrelevant "Your shopping cart is empty!" message is displayed in the search results after there are no products matching the search criteria.

**Expected result:** The relevant "No exact matches found" message indicating that there are no products matching the search criteria is displayed in the search results.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/uj9tish2izh6fk1d0lmcf/hw3_bug_4.mp4?rlkey=z7heac7sd1zw4y959qphdnn71&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/6j56pu7yhln0tulb3meji/hw_3_bug_4.png?rlkey=mmtp4t6fj35gt50wkuy6q5wpx&dl=0)

---
### ID-16: Only four products for comparison are displayed on the "Product Comparison" page after adding five products for comparison.

**Description:** Only four products for comparison are displayed on the "Product Comparison" page after adding five products for comparison.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net/.
2. Log into the account using valid credentials.
3. Click the "Dogs" category in the navigation menu.
4. Add 5 products to the comparison list using the icon.
5. Click the "Compare" menu in the header.
6. Pay attention to the quantity of products to compare.

**Actual result:** Only four products for comparison are displayed on the "Product Comparison" page after adding five products for comparison.

**Expected result:** Five products are displayed on the "Product Comparison" page after adding this amount of products for comparison.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/j6zp89lp8spj8hmu1adb1/hw3_bug_6.mp4?rlkey=d6s8e1hzrbogxtf40oyq29n4u&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/re8n2niqxxa01xh0ggk6d/hw_3_bug_6.png?rlkey=fxp6cbsbwpjwu7mbv4bmb0bre&dl=0)

---
### ID-17: The empty product comparison menu with the one item in the list instead is shown in the header menu.

**Description:** The empty product comparison menu with the one item in the list instead is shown in the header menu.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net/.
2. Log into the account using valid credentials.
3. Click the “My Account” menu.
4. Choose the “My Account” section from the drop-down menu.
5. Pay attention to the “Compare” menu.

**Actual result:** The empty product comparison menu with the one item in the list instead is shown in the header menu.

**Expected result:** The empty product comparison menu with zero value is displayed in the header menu.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/675yppwgffrkemdiev69v/hw3_bug_5.mp4?rlkey=ikj4rgnswmrxu3385yfpmh6pv&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/q8sjbu3nht5yvw3bdcccc/hw_3_bug_5.png?rlkey=vxyhtgbjl2w0fgqkb26y9virm&dl=0)

## Category: Homework-4

Task 1: Find 1-3 existing bugs on any website accessible via desktop devices on the Internet. The [EXE.ua](https://exe.ua/en/) website has been chosen.

---
### ID-18: The numbers and special characters are accepted in the "First Name", "Middle Name", and "Last Name" fields on the sign-up page.

**Description:** The numbers and special characters are accepted and saved in the "First Name", "Middle Name", and "Last Name" fields on the sign-up page after clicking the "Sign up" button.

**Steps To Reproduce:** 
1. Open the site https://exe.ua/en/
2. Click the "Sign up" button in the header.
3. Enter special characters and numbers in the "First Name", "Middle Name", and "Last Name" fields.
4. Fill in the remaining fields with valid data.
5. Click the "Sign up" button.
6. Pay attention to the accepted data.

**Actual result:** The numbers and special characters are accepted in the "First Name", "Middle Name", and "Last Name" fields on the sign-up page after clicking the "Sign up" button.

**Expected result:** Only alphabetical characters are accepted in the "First Name", "Middle Name", and "Last Name" fields on the sign-up page.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/ayw9guco44if71em5m9z3/hw4_bug_1.mp4?rlkey=a0zyzr1v8fmi2ovkzshfoil0l&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/t68hmqyasqjalppiafbua/hw4_bug_1.png?rlkey=bui54gdr12dlqtkv4qh3683z7&dl=0)

---
### ID-19: The negative numbers are accepted on the "Price" filter block after entering the value manually.

**Description:** The negative numbers are accepted on the "Price" filter block after entering the value manually.

**Steps To Reproduce:** 
1. Open the site https://exe.ua/en/.
2. Choose "PC accessories" / "Video Cards" in the "Catalog" sidebar.
3. Input negative numbers in the "from" price field.
4. Click the "Filter products" button.
5. Pay attention to the "from" price field.

**Actual result:** The negative numbers are accepted on the "Price" filter block after entering the value manually.

**Expected result:** The price fields are highlighted in red on the "Price" filter block after entering a negative value.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/gfarbc6gdaxpq6k3hoz3o/hw4_bug_2.mp4?rlkey=ogryd5aqu84f5se68cf6il5pu&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/0cw6otjlctpf3kdnjiequ/hw4_bug_2.png?rlkey=6294jd2mmpfmm4i3vvwemhddw&dl=0)

---
### ID-20: The text entry field is not marked as mandatory in the “Quality department” form.

**Description:** The text entry field is not indicated by an asterisk on the feedback form after clicking the “Quality department” link.

**Steps To Reproduce:** 
1. Open the site https://exe.ua/en/
2. Click the “Quality dept.” link in the right bottom corner.
3. Pay attention to the text entry field.

**Actual result:** The text entry field is not indicated by an asterisk on the feedback form after clicking the “Quality department” link.

**Expected result:** The mandatory status of the text entry field before the form submission is shown on the feedback form.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/itiju3bxxavht42x5k0lf/hw4_bug_3.png?rlkey=5di7yrwz14kobtdi61t8mjrvs&dl=0)

---
Task 2. Create bug reports in the Mantis bug tracker, found on the [test site](http://opencart.qatestlab.net/) on desktop devices.

---
### ID-21: Negative quantity entries are accepted on the “Dry Cat Food” product page after clicking the minus “QTY” (quantity) button.

**Description:** Negative quantity entries are accepted on the “Dry Cat Food” product page after clicking the minus “QTY” (quantity) button.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net
2. Open the “Dry Cat Food” product in the “Bestsellers” section.
3. Use the minus button to set negative product quantity.
4. Pay attention to the “QTY” field.

**Actual result:** Negative quantity entries are accepted on the “Dry Cat Food” product page after clicking the minus “QTY” (quantity) button.

**Expected result:** Negative quantity values are not accepted for entering on the “Dry Cat Food” product page after clicking the minus “QTY” (quantity) button.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/zz7ke25acpclet96g9wtd/hw4_bug_4.mp4?rlkey=ykhwusfessndr85288fwbxjjx&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/n3j9ae88ojs052x4dt5q9/hw_4_bug_4.png?rlkey=y0kytthe5lr2huqmdgaincxzr&dl=0)

---
### ID-22: The “Compare this Product” interactive icon is misaligned after hovering the mouse over the product picture.

**Description:** The “Compare this Product” interactive icon is misaligned after hovering the mouse over the “Dry Cat Food” product picture.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Scroll down to the “Bestsellers” section.
3. Hover the mouse over the “Dry Cat Food” picture.
4. Pay attention to the “Compare this Product” icon alignment.

**Actual result:** The “Compare this Product” interactive icon is misaligned after hovering the mouse over the “Dry Cat Food” product picture.

**Expected result:** The “Compare this Product” interactive icon is correctly aligned in a single vertical line after hovering the mouse over the “Dry Cat Food” product picture.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

The misalignment is reproducible for all products featuring the “Compare this Product” interactive icon.

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/by75lvrekf1smv17ul3yf/hw_4_bug_5.png?rlkey=sysx745zub4ivn6djopd3u1oe&dl=0)

---
### ID-23: The interactive icons are not displayed in the “Bestsellers” section after hovering the mouse over the “Parrot toys” product.

**Description:** The interactive icons “Add to Wish List”, “Quick view”, and “Compare this Product” are not displayed in the “Bestsellers” section after hovering the mouse over the “Parrot toys” product.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Scroll down to the “Bestsellers” section.
3. Hover the mouse over the “Parrot toys” picture.
4. Pay attention to the absence of interactive icons.

**Actual result:** The interactive icons “Add to Wish List”, “Quick view”, and “Compare this Product” are not displayed in the “Bestsellers” section after hovering the mouse over the “Parrot toys” product.

**Expected result:** The interactive icons “Add to Wish List”, “Quick view”, and “Compare this Product” are displayed in the “Bestsellers” section after hovering the mouse over the “Parrot toys” product.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This issue is also replicated in the following products:
- Petown Soft sided Pet Carrier pet Carriers Airline Approved with Foldable and Washable (Gray)
- Exo Terra Crystal Cave, Medium

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/8le2jx3rwc24eclk8zsf1/hw4_bug_6.mp4?rlkey=53rbxgycn7hopr88yj0t43m2t&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/2obbv4j72ypnwx4meoqga/hw_4_bug_6.png?rlkey=shwcgfr89dxkpfc2bvy1qgvvr&dl=0)

---
### ID-24: The success message is not displayed on the page after adding a product to the wish list from the product page.

**Description:** The success message is not displayed on the bottom notification area of the page after adding the “Dry Cat Food” product to the wish list from the product page.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net
2. Open the “Dry Cat Food” product in the “Bestsellers” section.
3. Click the “Add to Wish List” link.
4. Pay attention to the absence of a success message.

**Actual result:** The success message is not displayed on the bottom notification area of the page after adding the “Dry Cat Food” product to the wish list from the product page.

**Expected result:** The success message is displayed on the bottom notification area of the page after adding the “Dry Cat Food” product to the wish list from the product page.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/5jgjehq4f3fk2e6japmqi/hw4_bug_7.mp4?rlkey=ws42yqbhek5oqismwvnaqn572&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/m3xacivy817u20qndyzp5/hw_4_bug_7.png?rlkey=273p8e1eppn03lls5m5mx567y&dl=0)

---
### ID-25: The review is sent to the webmaster for approval on the product page after submitting it with an empty mandatory “Name” field.

**Description:** The review is sent to the webmaster for approval on the “Dry Cat Food” product page after submitting it with an empty mandatory “Name” field.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Open the “Dry Cat Food” product in the “Bestsellers” section.
3. Click the “Write a review” button.
4. Leave the “Your Name” field empty.
5. Fill in the “Your Review” field and select a review rating.
6. Click the “Continue” button.
7. Pay attention the review is sent for approval.

**Actual result:** The review is sent to the webmaster for approval on the “Dry Cat Food” product page after submitting it with an empty mandatory “Name” field.

**Expected result:** The error message about the necessity to fill the mandatory “Name” field is displayed on the product review section after clicking the “Continue” button.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 118.0.5993.118 (64-bit),
- Opera 104.0.4944.28.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/6wzamndhdlaq5vo2zsxd2/hw_4_bug_8.mp4?rlkey=q11qb3mtb6y5o2nonkzon7991&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/20c2jlj1hkzpr50zfkwj8/hw_4_bug_8.png?rlkey=yf9gicc4k4wspdm4y8lx4lddt&dl=0)

---
## Category: Homework-5

Task: Create bug reports in the Mantis bug tracker, found on the [test site](http://opencart.qatestlab.net/) on desktop devices.

---
### ID-26: The “Price (High > Low)” filter is displayed on the “Dogs” category page after applying the “Price (Low > High)” filter.

**Description:** The “Price (High > Low)” filter is displayed on the “Dogs” category page after applying the “Price (Low > High)” filter.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Choose the “Dogs” menu item.
3. Apply the “Price (Low > High)” filter.
4. Pay attention to the “Sort By” filter field.

**Actual result:** The “Price (High > Low)” filter is displayed on the “Dogs” category page after applying the “Price (Low > High)” filter.

**Expected result:** The “Price (Low > High)” filter is displayed on the “Dogs” category page after applying the “Price (Low > High)” filter.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 119.0.6045.106 (64-bit),
- Opera 104.0.4944.36.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/e52l3j1e8gfmr9wvti8nv/hw5_bug_1.mp4?rlkey=83xil2mg1paegzcwhgka6z1i7&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/tjwvbfxxoxu2thhnds41h/hw_5_bug_1.png?rlkey=xx6vkg9k4ay16u2702wak6bj0&dl=0)

---
### ID-27: The phone number isn’t updated on the “My Account Information” page after editing.

**Description:** The “Telephone” field isn’t updated on the “My Account Information” page after clicking the “CONTINUE” button.

**Preconditions:**
1. The user is registered and logged in.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Open the “My Account” page.
3. Click the “Edit your account information” link.
4. Update the “Telephone” field.
5. Click the “CONTINUE” button.
6. Click the “Edit your account information” link.
7. Pay attention to the “Telephone” field.

**Actual result:** The “Telephone” field isn’t updated on the “My Account Information” page after clicking the “CONTINUE” button.

**Expected result:** The updated telephone number is displayed on the “My Account Information” page after editing.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 119.0.6045.106 (64-bit),
- Opera 104.0.4944.36.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/mitghodvxhrbxx9wt20yl/hw5_bug_2.mp4?rlkey=4mx1znchwm2fojnzegwxx2wc2&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/rdd4faykeykobrcsm2ot2/hw_5_bug_2.png?rlkey=1o8eq0x5et1r5gy4vfk0soyh0&dl=0)

---
### ID-28: The error message is displayed on the “Change Password” page after entering the same passwords in the fields.

**Description:** The “Password confirmation does not match password!” error message is displayed on the “Change Password” page after entering the same passwords in the “Password” and “Password Confirm” fields.

**Preconditions:**
1. The user is registered and logged in.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Open the “My Account” page.
3. Click the “Change your password” link.
4. Fill in the “Password” and “Password Confirm” fields with valid data.
5. Click the “CONTINUE” button.
6. Pay attention to the error message.

**Actual result:** The “Password confirmation does not match password!” error message is displayed on the “Change Password” page after entering the same passwords in the “Password” and “Password Confirm” fields.

**Expected result:** The user is redirected to the next password change step after entering the same passwords in the “Password” and “Password Confirm” fields.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 119.0.6045.106 (64-bit),
- Opera 104.0.4944.36.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/c3nw8m9fydcz8rgupd5j1/hw5_bug_3.mp4?rlkey=ty9uekfcqve4ixq0e88w837z4&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/tzj85ikkwzvx65l99qh6w/hw_5_bug_3.png?rlkey=jxcz4os1wuvd8yxgijvg707pd&dl=0)

---
### ID-29: The saved address is not deleted on the “Address Book” page after clicking the “DELETE” button.

**Description:** The saved address is not deleted on the “Address Book” page after clicking the “DELETE” button.

**Preconditions:**
1. The user is registered and logged in.
2. Two or more addresses are saved on the “Address Book” page.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Open the “My Account” page.
3. Click the “Address” link.
4. Click the “DELETE” button near the saved address.
5. Pay attention to the address book entries.

**Actual result:** The saved address is not deleted on the “Address Book” page after clicking the “DELETE” button.

**Expected result:** The saved address is deleted on the “Address Book” page after clicking the “DELETE” button.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 119.0.6045.106 (64-bit),
- Opera 104.0.4944.36.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/wlu9hfzow2izqegh5xice/hw5_bug_4.mp4?rlkey=rwb6r9uvm84me4zyzpxtekj65&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/8i0c7uld7vsqlumzxuht9/hw_5_bug_4.png?rlkey=xhovckamzoz3sc2leuwgw9egk&dl=0)

---
### ID-30: The “Downloads” page isn’t displayed after clicking the “Downloads” link from the “My Account” menu.

**Description:** The “Order History” page instead of the “Downloads” page is displayed after clicking the “Downloads” link from the “My Account” menu.

**Preconditions:**
1. The user is registered and logged in.

**Steps To Reproduce:** 
1. Open the site http://opencart.qatestlab.net.
2. Open the “My Account” page.
3. Click the “Downloads” link.
4. Pay attention to the opened page.

**Actual result:** The “Order History” page instead of the “Downloads” page is displayed after clicking the “Downloads” link from the “My Account” menu.

**Expected result:** The “Downloads” page is displayed after clicking the “Downloads” link from the “My Account” menu.

**Environment:** Firefox 119.0 (64-bit) Windows 11 Enterprise

**Additional Information:** 

This bug is additionally observed in browsers:
- Google Chrome 119.0.6045.106 (64-bit),
- Opera 104.0.4944.36.

Attached video: [View the demonstration of the issue in this video](https://www.dropbox.com/scl/fi/l65izhzwum4p6fek25u00/hw5_bug_5.mp4?rlkey=ocfi8uvek5zn84osegdkkkl6o&dl=0)

**Attachments:** ![Screenshot of a bug](https://dl.dropboxusercontent.com/scl/fi/gciv0ae2tzxqfvke76q1h/hw_5_bug_5.png?rlkey=bm8z42sbidvt61xgwyr0lrn4u&dl=0)

---
