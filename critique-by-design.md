| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Data Critique and Redesign: Global pet ownership data
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

After looking through the different data sets and articles on the Makeover Monday website, I decided to go with one that had a topic that peaked my interest- pets. This was the original data visualization.
<img width="1702" height="816" alt="image" src="https://github.com/user-attachments/assets/2f42c8b4-4fb7-4d6a-a277-38e2f016f7c5" />


## Step two: the critique
There were many things that I liked about this visualization:

At the same time, there were many things that were not working for this visualization.

After reading Stephan Few's model on Effective Data Visualization, I can to the conclusion that this visualization was

## Step three: Sketch a solution
I first started by writing out what I though the original graphic was trying to accomplish- comparison of countries and comparison of pets within countries. I also realized that this data was more declarative than it was exploratory, and more data driven than conceptual- which led me to categorize this data visualization as an 'Everyday Data Viz', as referenced in the Good Charts textbook. 

I think moved into a few simple sketch ideas. My instinct was to do a bar chart, as this would allow the audience to make quick comparisons. 

I realized that drawing each of these by hand was not going to lead to the precision I wanted, especially with a stacked bar chart visualization model- so I turned to Tableau. 

<div class='tableauPlaceholder' id='viz1758060552891' style='position: relative'><noscript><a href='#'><img alt='How Does Pet Ownership differ around the World?Percentage of populations who own Dogs, Cats, Fish, and Birds ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PetOwnership-Version1&#47;version1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PetOwnership-Version1&#47;version1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pe&#47;PetOwnership-Version1&#47;version1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

There were things that I ideally would fix, including changing the vertial country names to have a slant, moving the x axis lable to the bottom of the graph. 

## Step four: Test the solution

When getting feedback from my peers, I decided not to prompt them with any questions at first, but simply showing them the data visualization. My intention here was to make sure that my graphic could speak for itself. If questions naturally came up, I would immediately see which aspects could be improved.

Once I recieved feedback (listed below in the table) I asked more specific questions, like:

1) Is the title clear?
2) Does the subtitle help add context?
3) Would it be helpful to put an example of how to interpret the graphic in the comments at the bottom? Or does this mean that the graphic cannot speak for itself?
4) Do the percentages confuse you?
5) Are the axises clear? Should I switch them. 


Results: 


| Interviewee | Feedback 1 | Feedback 2 |
|-------------|------------|------------|
|  Student 1  |    The vertical position of the country names made it difficult to read, is it possible to put them at a slant?    |     I had to think twice about whether the title meant people or households, but the subtitle helped    | 
|  Student 2  |      Because the data adds up to over 100% and the data isn't showing how many people in each country own a pet, but specific pets, what if you separated the pet categories to be side by side?       |  Could switching the columns and rows help to be able to read the countries better?  | Is there a reason you chose to organize your data this way?- showing dogs?  |
|  Student 3  |    It is difficult to differentiate between the shade of blue and green- increased contrast would help        |   is you separate the pet categories, it is easier to see the differences in the colors     |

Synthesis: 

From this feedback from my peers, I realized that overall I had an ok visualization and it was aligned with the story I wanted to tell. What was consistent was that the stacked bar graph wasn't working with this data, for a few reasons
1) the data wasn't about the percentage of people who own a pet in each country, but the percentage of people who owned specific categories of pets each kind of pet
2) the data added up to over 100%- which made sense after a few minutes, but wasn't initially intuitive as to why
3) there was the possibility for overlap between pet categories- people could own multiple types of pets
4) the stacked bar graph leads you to look for the country that owns the most pets, which is not what the data represents

All of the interviewees agreed that a version of a side by side bar chart might work better- so I tried that!

I also realized in the process of embedding my tableau visualizations to this site, that I needed to adjust my tableau setting to have the visualization fit the entire page- a setting I would need to adjust for my next version.


## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

