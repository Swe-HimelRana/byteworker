
# byteworker
Convert byte to word and world to decimal
## Version: 1.0.0

## Background
 We are developing an automaton system. where hardware send data through post request but send only byte without any headers and formatting.
 I have just build this package for working with this kind of situation easily

# example input

<code>
b'\\xd2\\x04.\\x164#\\x80\\r'
</code>
<br>
or <br>
<code>
b'\xd2\x04.\x164#\x80\r'
</code>

# Output
[1234, 5678, 9012, 3456]

##  Available Functions

    is_byte_has_double_slash() 
	    1. return True or False
	    
    double_slash_to_sinble_slash() 
	    1. Fix byte \\ issue convert it to \ 
	    
    get_perfect_byte() 
	    1. Return perfect bye if it ha \\ change to \
	    2. If it has \ just return it
	
	byte_to_word_to_decemal_array()
		1. It receive a byte and return decimal array by word	    

# Enjoy

  

If you like please give a star
[Portfolio](https://himelrana.com) | [Send a mail](mailto:contact@himelrana.com)