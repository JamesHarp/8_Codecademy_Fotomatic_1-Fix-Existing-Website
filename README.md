# Fotomatic
Fotomatic is [Project #8](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-making-a-website-responsive/modules/wdcp-22-learn-css-documentation-and-debugging-679e7a04-ff8b-4693-a364-fa420794d1be/informationals/f1-2-c1p1-fotomatic) in the Codecademy [Full Stack Engineer Career Path](https://www.codecademy.com/career-journey/full-stack-engineer).  The aim of the project is to correct the mistakes in the sample project to match the specification.  For practice, I am budling the project from scratch to match the specification after first fixing and then rebuilding the broken site.

## Resources
### [Specification](https://content.codecademy.com/courses/freelance-1/capstone-1/specs/fotomatic_spec_landing_v2.png?_gl=1*zz9e2o*_ga*MjI5MTY3NjMzLjE2NjQxNzE0MTU.*_ga_3LRZM6TM9L*MTY3NzY0NTY2Ny42Mi4xLjE2Nzc2NDcyNTMuNDMuMC4w)
![enter image description here](https://content.codecademy.com/courses/freelance-1/capstone-1/specs/fotomatic_spec_landing_v2.png?_gl=1*zz9e2o*_ga*MjI5MTY3NjMzLjE2NjQxNzE0MTU.*_ga_3LRZM6TM9L*MTY3NzY0NTY2Ny42Mi4xLjE2Nzc2NDcyNTMuNDMuMC4w)

### [Reference (Working Site)](https://content.codecademy.com/courses/freelance-1/capstone-1/solution/index.html?_gl=1*t7f2ie*_ga*MjI5MTY3NjMzLjE2NjQxNzE0MTU.*_ga_3LRZM6TM9L*MTY3NzY0OTkyOS42My4xLjE2Nzc2NTAxMDkuNTcuMC4w)

## 1. Fix Broken Site
### Issues fixed
- [x] No styling applied to site
	-  style.css linked to index.html
- [ ] Fix missing images
	- [x] Fix missing Instagram logo in header
	-   incorrect path to image
	- [x] Fix missing banner image
		- background-image:  url("../images/banner-landingpage.jpg");
		- background-size:  cover;
		- background-position:  bottom;
	- [x] Fix missing features images
		- <img  src='./resources/images/feature-1.png  />'
		- 	<img  src='./resources/images/feature-1.png  />' 
		- [x] Fix features image sizing
		- .image-container  img  {
				display:  block;
				width:  100%;
				}
		- .feature  .content  {
				padding:  40px  0;
		}
- [x] Centre and pad (left) sign up call to action
- #sign-up-cta  {
position:  relative;
left:  10%;


