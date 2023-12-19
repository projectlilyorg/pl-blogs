# Backend Layout

## Folder Structure

- content.json
- mission.txt
- vision.txt
- Blogs
  - 1
    - 1.jpg
    - 1.txt
  - ...
- Posters
  - 1
    - 1.jpg
    - 1.txt
  - ...

## File Contents

### content.json

> Contains the data about number of Blogs and Posters in the repository.

Format :

        {
           "Blogs" : "<Total number of blogs>" ,
           "Poster" : "<Total number of posters>"
        }

Example:

    {
      "Blogs":3,
      "Posters":2,
    }

### blogs/n/n.txt

> Contains the blog data. The first line text will be taken as title. From the second line data will be considered for body

Format:

    L1:Heading
    L2:data

Example:

    Deep Within
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean in ornare velit, sed porttitor metus. Phasellus elementum feugiat purus, ac blandit enim ultrices a. Phasellus nisl ipsum, consequat a ante varius, fermentum semper mi. Morbi egestas, libero ac dignissim tincidunt, tellus nisl facilisis diam, nec placerat nisl lorem ac tortor. Nullam vehicula vel tortor non sollicitudin. Duis sit amet mauris nec tellus dapibus ultricies. Nulla bibendum nisi eu risus consequat, ut sollicitudin turpis sodales.
