DOM clobbering hints:

- Some elements (by name/id) can become global properties on window.
- The check is window.isAdmin === true.
- Can you make window.isAdmin equal 	rue via HTML injection?

(Players may solve by discovering the pitfall; you can adjust difficulty later.)
