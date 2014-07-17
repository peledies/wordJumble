wordJumble
==========

create a string of concatenated single syllable words


###Usage

```PHP
<?php
require "WordJumbleClass.php";

$jumble = new WordJumble();
$jumble2 = new WordJumble(5,'prefix_',false);

echo "Default: ".$jumble->string."</br>";
echo "Custom: ".$jumble2->string."</br>";
?>
```

###Example Output

    Default: suchCrampFitchTurfNag6
    Custom:  prefix_sunAndCraftPuppyCask
