# Josh's TextMate Utilities

This bundle is a collection of commands, macros, and snippets that I've found useful. If you find anything useful feel free to use it. If you see anything that can be improved on please let me know.

*	**select between quotes**  
	Selects text between pairs of single or double quotes
	
*	**select between tags**  
	Selects text between pairs of HTML or XML tags
	
*	**HTML tags to lowercase**  
	Converts HTML tag names to lowercase
	
*	**mailto**  
	Inserts a simple HTML *mailto:* link
	
*	**normalize spaces**  
	Converts all spaces (single, multiple, non-breaking, etc) to a single space in the selection
	
*	**remove blank lines in selection**  
	Strips blank lines, including lines containing only whitespace, from the selection
	
*	**nice quotes**  
	Converts matching pairs of regular quote HTML entities (&amp;quot;some text&amp;quot;) to curly quote entities (&amp;ldquo;some text&amp;rdquo;)
	
*	**Google-Hosted jQuery**  
	Inserts the path to the Google CDN-hosted jQuery script
	
*	**jQuery ready**  
	Inserts the safe, shorthand jQuery ready function
	
*	**re-indent xml**  
	Nicely indents a string of XML that's been unwrapped onto one line, to make it more readable
	
	

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/superconnected/joshs-tm-utils.tmbundle.git "Josh's TM Utilities.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/superconnected/joshs-tm-utils.tmbundle/tarball/master
    tar zxf superconnected-joshs-tm-utils.tmbundle*.tar.gz
    rm superconnected-joshs-tm-utils.tmbundle*.tar.gz
    mv superconnected-joshs-tm-utils.tmbundle* "Josh's TM Utilities.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'