Front-end-Style-Guide
=====================

JQuery

Specify a function to execute when the DOM is fully loaded

    $(document).ready()
    $().ready() (this is not recommended)



Use delegate not live

    $(foo).live('click')
    $(foo).delgate('element','click')

