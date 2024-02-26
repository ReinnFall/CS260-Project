### Basics of Updating Respository
git add file.md  
git commit -m "updated the file"
git push

REMEBER TO SAVE THE FILE BEFORE DOING THESE STEPS

### HTML Basics 
<a href= "website URL">Placeholder Name</a>

img<src="address" alt="Placeholder Name" width=100> 

### Deploying Commands
./deployFiles.sh -k ~/Documents/BYU\ Assignments/2024\ Winter/CS260/VoltageVanity479.pem -h pogocheck.click -s simon

Switch simon to startup to deploy files there

### CSS 
*{} this will try to apply all style elements to all elements in html

If you want to specifically move the alignment of text in a CSS container, use this:

display: flex;
justify-content: left;

The container has to be a flex

When using viewport, you can make the text dynamically change size by setting the font size to 4vw. 

### JavaScript
## Random Functions
let s = 'Cats Dogs Rats Mice'; // string literal
s = new String('Cats Dogs Rats Mice'); // string object

console.log('casefold: ', s.toUpperCase(), s.toLowerCase());

console.log('split: ', s.split(' '));
    split:  (4) ['Cats', 'Dogs', 'Rats', 'Mice']
console.log('endsWith: ', s.endsWith('Mice'));
    true
console.log('replace: ', s.replace('Dogs', 'Puppies'));
    replace:  Cats Puppies Rats Mice
console.log('slice: ', s.slice(3, 7));
    slice:  s Do
 
## Regex
 const text = 'Both cats and dogs are pets, but not rocks.';

  const objRegex = new RegExp('cat.?', 'i'); // cat, cats, catz
  const literalRegex = /cat.?/i; // literal regex with flags
  console.log(text.match(literalRegex)); 

    ['cats', index: 5, input: 'Both cats and dogs are pets, but not rocks.', groups: undefined]

  
  const petRegex = /(dog)|(cat)|(bird)/gim; // global, case insensitive, multiline
    
  console.log(text.match(petRegex));
    ['cat', 'dog']
  console.log(text.replace(petRegex, 'animal'));
    Both animals and animals are pets, but not rocks.
  console.log(petRegex.test(text));
    true

