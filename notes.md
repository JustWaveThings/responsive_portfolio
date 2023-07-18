
# Responsive portfolio design from desktop to mobile

## Project Goals

- Responsive from Desktop to iPhone5
- Use following:
  - Use Art direction picture for responsive images
  - AA at minimum for accessibility benchmarks
  - Use media queries
- Match given design layouts to *approximate* pixel perfect reproduction, since I was only given PNG's to base my implementation on.

### Visible changes to adapt from Desktop/Tablet/Mobile

#### Things to consider

##### Section 1

- Photo uses art direction in both tablet and mobile
- Photo placement changes at each query
- In tablet, text wraps around photo and Name overlaps part of photo
- In mobile, name is back to being contained within image
- Tablet does not have the socials in section one
- Desktop Heading is left justified, tablet seems to be some form of centered, mobile is centered
- I believe text size remains consistent throughout queries.

##### Section 2

- Header is slightly smaller in Tablet only
- Slightly less margin between project rows on Tablet
- Everything else is the same, normal behavior of flex-wrap

##### Section 3

- Header and socials are center justified on mobile only, the others are left justified.
- layout for mobile goes to column, with no padding/margin around image, which is also art direction'd

#### Additional Information

- This project will have the two breakpoints of: 480px, 768px
  - mobile will be less than
