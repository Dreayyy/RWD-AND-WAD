
MIDTERM PROJECT: Web Application Development 1
Objective:
Work as a team to design and build a simple, functional, and well-structured web application using HTML, CSS, and minimal JavaScript. The goal is to practice collaboration, apply your understanding of front-end development, and deliver a polished final product.
Requirements:

Important: The concept should have at least 3 unique pages connected by navigation.


Technical Requirements:


HTML:
Use semantic HTML5 structure (<header>, <nav>, <main>, <section>, <footer>).
Include at least one form (contact form, search form, etc.) with proper input validation attributes.


CSS:
Use an external stylesheet (no inline styles).
Apply flexbox or grid for layout.
Include styling for hover states, buttons, and forms.
Use consistent colors, fonts, and spacing across all pages.


JavaScript (Minimal):
Use JS for one or more interactive features, such as:
A mobile menu toggle
Form validation (client-side)
Simple image slider or gallery
Show/hide content (accordion, tabs, etc.)
Code must be well-organized and readable (no unnecessary complexity).


Design Guidelines:
Use a consistent design theme (colors, typography, spacing).
Prioritize user experience: clean layout, easy navigation, clear content.


Deliverables:


Source Code: Complete HTML, CSS, and JS files.


—----------------------------------------------------------------------------------------


 everything  should  be semantic, professional, and readable.

Coffee Shop Website (Huevos’ Cafe)

Let’s level this up into a professional coffee shop website that looks polished, responsive (desktop + mobile full screen), and follows your project guidelines

gusto ko mobile first design ito, kasi gusto ko na maging responsive, so....mag start ito sa @media (min-width:601px

Default mobile view (0–600px) → single column, simple layout, stacked nav.


Tablet+ (601px) → nav goes to the right, 2-column menu grid, centered cart/checkout.


Desktop+ (1024px) → 3-column menu, wider container, left-aligned header/footer like professional websites


Gagawin nating mobile-first HTML structure na may burger menu toggle (hamburger icon sa maliit na screen) at full navigation kapag malaki na yung screen.
	
Burger menu toggle for small screens.


Full nav on tablet/desktop.

Let’s level this up parang FoodPanda-style swipe carousel for drinks and breads.
We’ll use mobile-first horizontal scroll (overflow-x), tapos sa malalaking screen magiging grid siya.


Full-Screen→ Big background image, text centered.


Better Visuals → Stock coffee shop/coffee cup images (via placeholders/unsplash links).


Responsive Layout → Looks clean on desktop & collapses neatly on mobile.


Polished Design → Dark coffee theme with contrast highlights.



🏠 Home Page →  welcoming  section  with shop name , logo and tagline + “Order Now” button.


📜 Menu Page → 

In the menu, first there is “drinks” and “pastries” button , if the user click the button they will be sent to the chosen button menu. After clicking the button , there will be a search icon where users can search specific items. 

instead of just listing items, user will first click the coffee to view the coffee description and the bigger picture of the item, here users can choose the size of the drink, andd users can also choose add-ons ( vanilla syrup, hazel nut, caramel syrup with - and + button) and condiments (white sugar, brown sugar with - and + button) the - button will only appear when + button is clicked , so each - and + will be tracked . There is “reset recipe” to reset the drink.. Each item will have an “Add to Cart” button.


🛒 Cart Page  → shows items added, total price, and checkout form.


✅ JavaScript → handles cart logic (add/remove items, update total).


Browse menu → add to cart → checkout with delivery info.
	Form → Name, Email, Address, Payment method.
Cart uses localStorage so data won’t disappear when navigating pages.

lahat may external CSS file (style.css) para consistent ang design at professional look.
 Full screen hero (desktop & mobile)
✅ Professional fonts + dark coffee color scheme
✅ Menu grid na responsive
✅ Working Add to Cart (localStorage based)
✅ Checkout form ready


Drinks and breads separated into categories.



User can scroll horizontally (swipe left/right) — super effective sa mobile.


update the cart.html page para makita yung chosen size + add-ons breakdown sa cart list
	
 extend the cart.html so the user can see a full breakdown:


Item name + size


List of add-ons (kung meron)


Price breakdown (base + add-ons + total per item)


Buttons: ➕ / ➖ to adjust quantity.
Option to remove item (❌ Remove button.)
Cart total
 idagdag din yung quantity (x2, x3, etc.) na may + / - buttons para mas pro pa, parang legit na ordering apps


 idagdag ko na rin yung checkout.html page with a simple order form (Name, Address, Payment option) para full flow na from order → cart → checkout?
Home → Menu → Cart → Checkout


Checkout page may order summary + form (Name, Address, Payment Option).


Pag-submit, magdi-display ng confirmation at automatic na lilinisin ang cart (para fresh next order).


confirmation.html
Acknowledges Success


It confirms to the user that their action went through.


Example: “✅ Your order has been placed successfully!”


Provides Order / Submission Details


Shows what the user just submitted or purchased.


Example: a summary of items in their cart, total price, and delivery info.


Gives Next Steps / Instructions


Tells the user what will happen next.


Example: “Your coffee will be ready for pickup in 15 minutes.”






