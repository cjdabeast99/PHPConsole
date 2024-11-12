# PHPConsole
Easily output PHP variables to the browsers console for debugging.


# The script
The script is very short and simple only being 12 lines. The debug function can take in array(s), string, int, booleans and log them to the console by converting to json encoded
then using console.log() in JS. You will just need to insert the debug file into an appriopriate file where it is always loaded.

# boolean paramater $with_script_tags
By default this is toggled on. But if you ever write PhP inside of JS and need to debug code that's where you will need to set this boolean to false.