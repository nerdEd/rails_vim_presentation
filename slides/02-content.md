!SLIDE bullets
# Basic Navigation in a Rails Application

* :Rcontroller - jump to controller relevant to current context or specify
  * :Rcon widgets -> app/controllers/widgets_controller.rb
  * :Rcon (from a lot of shit) -> app/controllers/widgets_controller

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
