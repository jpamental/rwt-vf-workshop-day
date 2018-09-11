# Responsive Web Typography Variable Font Workshop Day
Working files for the full-day version of my workshop on using variable fonts and modern CSS techniques.

## Initial setup
To make use of the `gulp` process, you need to have `npm` and `gulp` installed.

Once both are installed, follow these steps:
Open a terminal window and navigate to the project root
Execute the command `npm install`

## Running the `gulp` process
If the initial setup has been completed, executing the command `gulp` from the root of the project will start the 'watch' task and the local server with BrowserSync.

## Simple Setup (Plain CSS approach)
If you want to skip all the 'build tools' you can just edit the files in the `css` directory instead. Just remember that if you do that and then try the build process later, you will lose any changes you make to `rwt_vf_styles.css` so be sure to make a copy to bring those changes back into the source Sass file (located in `scss/rwt_vf_styles.scss`).

## What you'll find here
This repository contains all the sample pages from my workshop, along with some useful tools and supporting files.

### Supporting Directories:
- CSS - all the compiled CSS for the project. You can edit these directly but you will lose the changes if you then try out the `build` process
- Fonts - some early versions of variable fonts and Plex, and open-source font from IBM
- Images - images used in the project (all taken/created by me)
- Ish - a really useful tool from Brad Frost for previewing any page in a responsive 'viewer' to help test the responsiveness of your work
- JS - just a few script files to help enhance font loading and typography
- SCSS - the source Sass files for the project

### Pages
- index.html - This is an example of a 'finished' page that incorporates all the things covered in the course
- part-01
  - part-01_start.html - start with semantics! Just good, sensible HTML markup
- part-02
  - part-2_begin.html - what passes for 'done' all too often: styled (really for desktop) but not all that responsive
  - part-2_final.html - a really responsive typographic system, with scale, proportion, performance, and finesse in mind
- part-03
  - part-3_begin.html - building on what came before, getting ready to add in variable fonts
  - part-3_final.html - variable fonts added, but only for browsers that can support them
  - vf-samples.html - a page that has examples of individual axes of variation, triggered on hover
- part-04
  - part-4_begin.html - build on the variable font implementation with CSS custom properties for the variations
  - part-4_final.html - implement CSS custom properties throughout for any instance of font variations
- part-05
  - part-5_begin.html - build on the variable font implementation with CSS custom properties for rhe modular scaling
  - part-5_final.html - fully implemented dynamic typographic system
- part-06
  - part-06.html - a version of the final file in part 5, but with the calculations and custom properties being used 'where they should be' in 'font-weight', 'font-stretch' (and we'll see where that isn't working as it should)
- part-07-extras
  - index-meta.html - the same essay from part-06, but here complete with the CSS
  - example-magazine.html - a fictitious outdoor magazine site page, showcasing variable fonts, fluid typography, and a bit of CSS grid
- part-08-book - we can look at how this can be applied to a system (i.e. several chapter 'pages' referencing the same CSS), and an experiment in creating a different web-based reading experience
