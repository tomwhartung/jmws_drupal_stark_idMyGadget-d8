# jmws_drupal_stark_idMyGadget-d8-second_try

This is my second attempt to integrate idMyGadget [jmws_idMyGadget_for_drupal-d8](https://github.com/tomwhartung/jmws_idMyGadget_for_drupal-d8) with the default Drupal 8 theme Stark.

## This Repo Is No Longer Active

**Note that this repository does not contain working code, and is no longer being updated.**

### Details: What Doesn't Work

For some reason this theme does not allow blocks to be placed.

Worse than that, when I click on Save Blocks on this theme's Block Layout page, it removes all the blocks from bartik.  I mean wtf.

And curiously, when I use the same process to create a theme named idmygadget_stark (see the [jmws_drupal_idMyGadget_stark-d8](https://github.com/tomwhartung/jmws_drupal_idMyGadget_stark-d8) repo) it appears to work fine.

### Theory: As to Why This Theme Doesn't Work

After getting another copy of this theme to work, I believe the issues above are due to the theme's directory name,

Note that this theme's parent directory name is named "stark_idmygadget" and that hence all of the file names in that directory also start with "stark_idmygadget".

On a hunch, I started over with the same code but renamed the directory to "idmygadget_stark" and updated all of the files in that directory with similar names.

I did not experience any of these issues with that version, so I cannot help but suspect that the name is the source of the issues.

Live and learn, that's what we do!
