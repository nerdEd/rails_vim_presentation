!SLIDE bullets
# Basic Navigation in a Rails Application

* :Rcontroller - jump to related or specified controller
  * :Rcon widgets -> app/controllers/widgets_controller.rb
  * :Rcon (from related files) -> app/controllers/widgets_controller

* :Rmodel - second verse same as the first.

!SLIDE bullets
# Other friends that act similarly 
* :Rintegration (:Rint)
* :Rfunctional
* :Rinitializer
* :Rmailer
* :Rmigration
* ...

!SLIDE bullets
# Alternates to "R" commands

* RT* - open file in new tab
* RS* - open file in horizontal split
* RV* - open file in vertical split

!SLIDE bullets
# File Creation

* Any of the preceding navigation shortcuts can create files too.

## Example:
* :Rmodel kate_moss!

!SLIDE bullets

# :R - jump to a _related_ file

* model <-> schema
* controller <-> helper
* controller test -> controller

!SLIDE bullets

# :A - jump to an _alternate_ file

* model -> test
* schema -> migration
* controller -> test

!SLIDE

# `gf` for when c-tags is broken

!SLIDE bullets

# OK maybe gf is better than just that...

* jump to a partial from a reference in a view
* jump to a required file
* jump to ANY referenced file from... anywhere (docs, html, whatev.)
* jump to constant def

!SLIDE bullets

# :Rake

* `:Rake` executes the whole of the current test or migration (from the 
test or the related model/controller)

* `:.Rake` runs the test currently under the cursor (in specs/cukes)

!SLIDE bullets

# :Rinvert 
* generate down migration from up

!SLIDE bullets
# :Rextract
* pull selected portion of view into named partial

# :'<,'>Rextract snip
* generates `app/views/widgets/_snip.html.haml`
* selection =>  `= render :partial => 'snip'`

!SLIDE 

# Guess.

## Rails.vim is fairly intuitive once you get your head around the basics. If you think it might do something, try it. It might just work.
