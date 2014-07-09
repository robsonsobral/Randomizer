# Randomizer

Open this file: /plugins/pi.randomizer.php

Fill the array with as many quotes as you want.

Then place the following tag in any of your templates:

    {exp:randomizer:set_one}
    
    	To add another sets of quotes, add another function:
    
    	function set_two()
    	{
    		$quotes = array( FILL WITH QUOTES);
    
    		return $quotes[array_rand($quotes)];
    	}

Then use this tag in your template:

    {exp:randomizer:set_two}

Version 1.1
******************
- Updated plugin to be 2.0 compatible

