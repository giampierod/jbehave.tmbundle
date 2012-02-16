# JBehave TextMate Bundle

I couldn't find any full functional bundles for JBehave that had snippets as well as syntax highlighting for TextMate. I borrowed some code from the work done by devstopfix in his tmlanguage implementation. This should be good for most people to speed up their story building in JBehave. 

## Installation

	mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
	cd ~/Library/Application\ Support/TextMate/Bundles/
	git clone git://github.com/Gimped/jbehave.tmbundle.git
	osascript -e 'tell app "TextMate" to reload bundles'