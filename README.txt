Name: YourNameHere

Tools used: ChatGPT, Colab, Browser

Q1:

- Key finding (2-4 sentences):
Study hours show a strong positive linear relationship with exam scores. The trendline slope confirms that as study hours increase, scores increase consistently. Sleep hours appear less predictive because the points are more scattered. Overall, study time is the stronger predictor.

- Outlier:
Student C appears slightly above trend compared to others with similar study time.

Q2:

- What was broken:
The header was not aligned correctly on desktop, and the hero section did not stack properly on mobile.

- What I changed:
I added flexbox to the header and hero sections and implemented media queries for 900px and 600px breakpoints. I also centered the container and added padding.

Q3:

Prompt 1 (plan, no code):

How should I structure responsive breakpoints to create a 4-column grid on desktop, 2 columns on tablet, and 1 column on mobile, while also making a hero section that stacks on small screens?

Response snippet:

"You can use CSS Grid with media queries at 900px and 600px. For the hero section, use flexbox and change flex-direction to column under 600px."

Accepted:
- Using repeat() for grid columns
- Using flex-direction: column for mobile hero

Rejected:
- Using a CSS framework, because the instructions required no frameworks.

Prompt 2 (debug):

My hero section is not stacking on mobile. Here is my CSS:

.hero {
  display: flex;
}

Response snippet:

"You need a media query that sets flex-direction: column under 600px."

What I verified:
- viewport sizes tested: 375px, 768px, 1200px
- what I checked visually: header alignment, hero stacking, grid column count, image responsiveness

Q4:

- Chart caption:
This chart shows a strong positive relationship between study hours and exam scores.

- Decision based on chart:
I would recommend increasing structured study time to improve academic performance.
