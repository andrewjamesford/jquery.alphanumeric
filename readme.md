# jQuery Alphanumeric #


## Examples ##

### Only alphanumeric ###
$('.sample1').alphanumeric();

### Only alphanumeric + dot(.) + comma (,) and space ###
$('.sample2').alphanumeric({allow:"., "});

### Only lowercase alpha characters ###
$('.sample3').alpha({nocaps:true});

### Only numeric characters ###
$('.sample4').numeric();

### Only numeric characters and some exceptions like dot(.) ###
$('.sample5').numeric({allow:"."});

### Custom rule and define only certain characters to prevent like dot (.) one (1) and a (a) ###
$('.sample6').alphanumeric({ichars:'.1a'});

## API Functions ##
1. alphanumeric - allow both alphabet and numeric characters
1. alpha - allow only alphabet characters
1. numeric - allow only numeric characters
1. decimal - allow only numeric decimal characters

## API Properties ##
1. allow - add excempted characters to the rule of prevention
1. ichars - define a custom set of characters to prevent
1. allcaps - allow only capital letters to be entered
1. nocaps - allow only lowercase characters to be entered
1. decimal - set to one only allow decimal characters to be entered