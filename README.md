##### CSBase2016  / 18.17.0 CT Release  (0716)
##### Created: 7/20/16
##### Last Updated: 7/21/16
========

### Github URL
* github.com/Four51Repositories/CSBase2016

========

### Product Configuration


###### Sidebar(1) "Latest Products"
* Products assigned to a product category with an Interop ID of **EX_LatestProducts**

**Troubleshooting**
* Category must be active and have assigned products
* Category must be assigned to the company, group, or user

========

###### Sidebar(2) "Featured Products"
* Products assigned to a product category with an Interop ID of **EX_BestProducts**

**Troubleshooting**
* Category must be active and have assigned products
* Category must be assigned to the company, group, or user


========

###### Qualities ( New Store Opening, Multiple Languages, Product Video )

**Instructions**
* The Static Spec Group Name must be Qualities
* Use the FontAwesome icon library for additional icon options ( https://fortawesome.github.io/Font-Awesome/ ) 

**Examples**

*New Store Opening*
* Static Spec Group Name: Qualities
* Spec Name: New Store Opening
* Spec Value: `<i class="fa fa-star"></i> New Store Opening`

*Multiple Languages*
* Static Spec Group Name: Qualities
* Spec Name: Multiple Languages
* Spec Value: `<i class="fa fa-language"></i> Multiple Languages`

*Product Video*
* Static Spec Group Name: Qualities
* Spec Name: Product Video
* Spec Value: `<i class="fa fa-video-camera"></i> Product Video`

======== 

### Product Detail Template  


========

### Images
`css/images/custom/` 

========

### Fonts
`css/fonts` 

======== 
### OrderCloud Custom Solutions

###### Back To Top
`lib/oc/backToTop.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Back To Top
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Back%20To%20Top`

========

###### Bootstrap Carousel
`lib/oc/carousel.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Bootstrap Carousel
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Bootstrap%20Carousel`

**Specific naming convention**
* VerizonCarouselImage

========

###### Category Collapse
`lib/oc/categoryCollapse.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Category Collapse
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Category%20Collapse`

========

###### Category Modal
`lib/oc/categoryModal.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Category Modal
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Category%20Modal`

========

###### Checkout Item Summary
`lib/oc/checkoutItemSummary.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Checkout Item Summary
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Checkout%20Item%20Summary`

========

###### Contact Modal
`lib/oc/contactModal.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Content Modal
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Content%20Modal`

========

###### Fixed Footer
`lib/oc/fixedFooter.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Fixed Footer
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Fixed%20Footer`

========

###### Hamburger Navigation
`lib/oc/hamburgerNavigation.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Hamburger Navigation Subcategories
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Hamburger%20Navigation%20Subcategories`

========

###### Minicart
`lib/oc/minicart.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Mini Cart
`https://github.com/Four51Repositories/CustomSolutions/blob/master/Mini%20Cart/minicart.js`

========

###### Order Cloud Spec Forms
`lib/oc/specForms.js`

**Instructions**
* Follow instructions under Four51 Repositories OrderCloud-SpecForms
`https://github.com/Four51Repositories/OrderCloud-SpecForms`

========

###### Product Lightbox
`lib/oc/productLightbox.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Product Lightbox
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Product%20Lightbox`

========

###### Product List Add To Cart
`lib/oc/productListAddToCart.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Product List Add To Cart
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Product%20List%20Add%20to%20Cart`

========

###### Product Zoom
`lib/oc/productZoom.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Product Zoom
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Product%20Zoom`

========

###### Same As Shipping Checkbox
`lib/oc/sameAsShippingCheckbox.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Same As Shipping Checkbox
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Same%20As%20Shipping%20Checkbox`

========

###### Security Modal
`lib/oc/securityModal.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Security Modal
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Security%20Modal`

========

###### Terms Modal
`lib/oc/termsModal.js`

**Instructions**
* Follow instructions under Custom Solutions Library - Terms Modal
`https://github.com/Four51Repositories/CustomSolutions/tree/master/Terms%20Modal`

========

### Modified
###### js
`js/app.js`
* Custom Solutions module injection

`js/filters.js`
* Set the hidden category interop ID's / line 114

`js/directives/categorydisplay.js`
* Category Display / lines 1-11
* Category Display Inline / lines 13-24
* categoryDisplayCtrl / lines 26-39
* category Display (service) / lines 41-128

`js/directives/product.js`
* Product View Alternate / lines 11-19
* Product List Init / lines 21-63
* Dynamic Static Specs / lines 183-211

`js/services/categoryDisplayService.js`
* categoryDisplayService / lines 1-21
* categoryliststree / lines 22-33
* categorylistnode / lines 35-52


##### html
`index.html`
* AnswerDash (optional) / lines 21-23
* Hamburger Navigation / lines 34-36
* Bootstrap Carousel / lines 38-40
* Hide branding / lines 42-45
* Fixed Footer / line 50
* Back To Top / line 52
* Custom Solution Modules / lines 78-94
* Custom Services / lines 170-174
* Comment out tree for Fixed Footer module / line 190
* Category display / lines 216-217

`partials/categoryListTree.html`
* Category List Tree

`partials/categoryView.html`
* Custom Category Displays (Best & Latest Products) / lines 18-19

`partials/controls/categoryDisplay.html`
* Category Display

`partials/controls/categoryDisplayInline.html`
* Category Display Inline

`partials/controls/orderSummary.html`
* Collapsible Item Summary / lines 12-37

`partials/controls/shortProductViewMinimal.html`
* qty detail [ multiplier & uom ]  / lines 11-22