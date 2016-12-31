# direction
## Create web action with nearly natural language.

Direction was created with the idea of implementing action on websites by describing it with nearly natural language.

Goals:

* Create a core library to process "Words" (ultimately properties on a prototype) into actions.
* Provide BNF/EBNF grammar to define expected behavior.
* Allow compilation of Directions for reuse.
* Allow grammars to be loaded.
* Reference the EBNF structure in creating Words to help solve overloaded Words?
 * `to` in `move.to('bottom')` or `add.to('.juggling')` or `add('.fourth.ball').to.me`
