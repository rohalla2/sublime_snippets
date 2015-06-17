# Custom Sublime Snippets

This repository serves as a location to store sublime snippets that I have found useful. 

## How to Use

Place the folders within the User directory. This should be located at [Sublime dir]/Packages/User.  
Either navigate there directly or within Sublime go to [Sublime Text 2] -> [Preferences] -> [Browse Packages].

## Current Snippets

### JavaScript

#### console-log
typing 'log' then hitting tab will autocomplete to ```console.log('text');``` with "text" highlighted for replacement.

#### angular-watch
typing 'scope' then hitting tab will auto complete to the standard angular watch statement: 
```
$scope.$watch('value', function(val) {
	
});
```

### HTML

#### directive-brackets
Typing an empty HTML tag '<>' and hitting tab will autocomplete to a easily create a custom tag. This is useful for creating element directives in Angular.