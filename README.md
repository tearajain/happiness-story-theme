# The Happiness Story - Shopify Theme

Modern Shopify theme with dark design, gold accents, and three-column hero section. Based on extraction from official preview.

## 🎨 Design Features

- **Dark Modern Aesthetic**: Charcoal background (#2a2a2a, #3a3a3a) with premium feel
- - **Gold Accents**: #c4a26a for highlights and CTAs
  - - **Hero Section**: "Three ways to give" with three responsive columns
    - - **Professional Layout**: Clean header with navigation and cart
      - - **Responsive**: Works on all devices
       
        - ## 📁 Theme Structure
       
        - ```
          theme/
          ├── assets/
          │   ├── ths-design-tokens.css
          │   ├── ths2-header.css
          │   ├── ths2-base.css
          │   ├── ths2-components.css
          │   └── ths2-animations.css
          ├── sections/
          │   ├── hero-three-ways.liquid
          │   ├── header.liquid
          │   └── ...
          ├── snippets/
          ├── templates/
          │   └── index.json
          └── config/
              └── settings_data.json
          ```

          ## 🚀 Installation

          ### Step 1: Download Theme Files
          Clone this repository or download all files

          ### Step 2: Access Your Shopify Theme Editor
          - Go to Admin Dashboard
          - - Navigate to Online Store > Themes
            - - Click "Add theme" > "Upload file"
              - - Upload the theme files
               
                - ### Step 3: Customize
                - - Update colors in design tokens
                  - - Modify section content
                    - - Test on different devices
                     
                      - ## 🎯 Key Files to Update
                     
                      - ### 1. CSS Files (For Colors)
                      - - Update gold accent: #c4a26a
                        - - Update dark backgrounds: #2a2a2a, #3a3a3a
                          - - Modify text colors as needed
                           
                            - ### 2. Hero Section (hero-three-ways.liquid)
                            - - Three card layout
                              - - Customizable titles and links
                                - - Gradient backgrounds per card
                                 
                                  - ### 3. Header
                                  - - Logo with gold "HAPPINESS" text
                                    - - Navigation menu
                                      - - Cart and search icons
                                        - - "GET A QUOTE" button
                                         
                                          - ## 🎨 Color Scheme
                                         
                                          - | Element | Color | Hex |
                                          - |---------|-------|-----|
                                          - | Primary Dark | Charcoal | #2a2a2a |
                                          - | Secondary Dark | Dark Gray | #3a3a3a |
                                          - | Accent | Gold | #c4a26a |
                                          - | Text Primary | White | #ffffff |
                                          - | Text Secondary | Light Gray | #b0b0b0 |
                                          - | Background Light | Cream | #f5f1e8 |
                                         
                                          - ## 📝 Customization
                                         
                                          - ### Changing Colors
                                          - Edit CSS files in `/assets/` directory:
                                          - ```css
                                            --color-primary-dark: #2a2a2a;
                                            --color-accent: #c4a26a;
                                            --color-text: #ffffff;
                                            ```

                                            ### Modifying Sections
                                            Edit Liquid files in `/sections/` directory to change:
                                            - Section titles
                                            - - Button text
                                              - - Link destinations
                                                - - Card content
                                                 
                                                  - ## 🔧 Technical Details
                                                 
                                                  - - **Base Theme**: Shopify Dawn
                                                    - - **Template Language**: Liquid
                                                      - - **Styling**: CSS3 with custom properties
                                                        - - **JavaScript**: ES6+
                                                          - - **Browser Support**: Modern browsers
                                                           
                                                            - ## 📱 Responsive Design
                                                           
                                                            - - Mobile: Optimized for screens < 600px
                                                              - - Tablet: Screens 600px - 1024px
                                                                - - Desktop: Screens > 1024px
                                                                 
                                                                  - ## ✨ Features
                                                                 
                                                                  - - Three-column card section
                                                                    - - Announcement bar
                                                                      - - Features showcase
                                                                        - - Customer testimonials
                                                                          - - Newsletter signup
                                                                            - - Footer with links
                                                                              - - Search functionality
                                                                                - - Shopping cart
                                                                                  - - Mobile navigation
                                                                                   
                                                                                    - ## 🆘 Support
                                                                                   
                                                                                    - For issues or questions:
                                                                                    - 1. Check the documentation in each file
                                                                                      2. 2. Review the preview design
                                                                                         3. 3. Consult Shopify theme documentation
                                                                                           
                                                                                            4. ## 📄 License
                                                                                           
                                                                                            5. This theme is based on Shopify's Dawn theme and custom modifications.
                                                                                           
                                                                                            6. ---
                                                                                           
                                                                                            7. **Created for**: The Happiness Story
                                                                                            8. **Date**: 2026
                                                                                            9. **Version**: 1.0
