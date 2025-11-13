---
layout: project
title: Mechanical Synthesis
description: Product design project
technologies: [MATLAB, Microsoft Excel, Fusion360, 3D Printing, Band Saws, Drills, Sanding Tools]
image: /assets/images/mechanical-synthesis.jpg
category: coursework
---

Bending down to clean out litter can be a real pain, especially for people who have issues bending down or mobility issues. We also specifically cite pregnant women and people with weakened immune systems for mobility issues as well as toxoplasmosis (a parasitic infection caused by parasites common in cat litter that can infect developing fetuses and cause inflammation in the brain, eyes, and heart). This is why we decided to rework the way litter boxes work in order to create an easier, and hopefully safer disposal method for cat litter.

## Design Project | Selfsift  
A litter box that is a cylinder which rolls because of rotatable wheels that touch its perimeter and a grate to catch feline waste as cylinder rotates, still allowing litter to pass through. Ideally it would be operated with a foot pedal and gearing that rotates said wheels so no one has to bend down, and the grate would mean no contact wtih waste is necessary. (Because of time and budget constraints we went with a hand crank to complete the design)

**Competitive Analysis, Prior Art Search, & Prospective User Interviews**  
We began by analyzing the market and what other litter disposal simplification tools were out there. We identified a few competitors and determined our most critical competitors were automatic litter boxes, which are expensive and don't look great in the home, and semi-automatic litter boxes, which have poor aesthetics and functionaity issues like noisy motors. We determined we could create a design that is cheaper, still highly functional, and more aesthetically acceptable than both by not using motors and keeping it similar to the same footprint as a normal litterbox.
![Cost Vs Convenience MATLAB]({{ "/assets/images/selfsift-cost-vs-convenience.jpg" | relative_url }}){: .inline-image-1 style="width: 565px"}

We also searched for patents that might interfere with our plan for this product.

Patent #: US5361725A  
Description of Product & Relevance:
- Box enclosure containing litter chamber and a distinct, separate antechamber.  The antechamber has arrangeable panels designed to provide a path from the entrance of the box to the litter area.  The idea is that on its way back, any litter the cat tracks on its paws will be caught in the antechamber rather than outside the box.
    - Relevant to our problem because a common issue among our interviewees was litter ending up around the house.
    - Different from our design so no real issue.

In terms of interviews, we did six interviews with different cat owners asking the following questions:
- Do you own cats?  If so, how many?
- How do you currently clean up after your cats?
- What’s the most annoying thing about cleaning up your cat's litter?
- What’s your least favorite part about the entire process?
- What is the most annoying thing about litterboxes?
- How often do you stop whatever task you're doing to clean your litterbox?
- What is stopping you from buying one of those self-cleaning litterboxes?
- Have you heard of toxoplasmosis and its impact on pregnant women?  

We found that cat owners faced a few issues spanning from physical discomfort during cleaning sessions to concerns regarding potential health hazards. The act of cleaning a traditional litter box often requires cat owners to assume uncomfortable positions, such as bending down, crouching, or kneeling, which can be particularly burdensome for individuals with mobility issues and those who find such movements arduous. There exists a clear unease surrounding the handling of cat waste directly, given the inherent risk of exposure to harmful bacteria and the potential emergence of health complications. This apprehension is clearest among immunocompromised individuals, pregnant women, and all cat owners wanting a sanitary living environment for themselves and their pets. 

**Initial Prototype**  
For our initial prototype we created a base out of plywood, ordered wheels and axles to attach to the base, 3D printed the cylinder that would be rotating, and had a litter grate laser cut out of acrylic. We also used wood, and a hand crank to turn one of the axles, thus allowing the wheels to rotate and rotate the cylinder with them.

![Selfsift Base]({{ "/assets/images/selfsift-base.jpg" | relative_url }}){: .inline-image-1 style="width: 250px"}
![Selfsift Prototype 1]({{ "/assets/images/selfsift-prototype1.jpg" | relative_url }}){: .inline-image-1 style="width: 260px"}

One issue was that for a cat to sit inside the litterbox and use it, it couldn't just freely it had to be able to remain stationary.
![Litter Sizes]({{ "/assets/images/litter-sizes.jpg" | relative_url }}){: .inline-image-r style="width: 180px"}
We also simulated the sifting accuracy using wood chips of varying sizes, but were slightly disappointed. However, we could easily improve our numbers with a few more minor modifications.

We found that the product recovered the most clean litter when it lost the most chunks, and vice versa. So, our current grate required
![Litter Sift]({{ "/assets/images/litter-sift.jpg" | relative_url }}){: .inline-image-r style="width: 180px"}
the user to jerk around the rotating mechanism in order to get the clean litter to fall through. In that process, dirty litter escaped, which is what we wanted to avoid. In order to address this problem, we made a new grate that sealed better to the dimensions of the cylinder and had smaller holes. In order to meet our criteria, we needed to improve sifting accuracy by 6% and clean litter recovery by 19% which seemed reasonable to us.

**Final Prototype**  
Our final prorotype was close to our ideal version of what we wanted. We solved the rotational issue by using strong strings and having a triangular cutout in the side of the cylinder. The springs were attached to triangular pieces of wood that, while pushed into the cylinder cutout, locked the cylinder in place. We also laser cut a new grate that increased our sifting efficiency the way we wanted it to. Due to time constraints we were not able to create a foot pedal that was connected to gears that would rotate the cylinder, but that would have been our ideal final solution. We also attached the grate to a cover for the top half of the cylinder so everything would be contained while the cylinder rotates and sifts. Below is our final prototype Bill of Materials; anything not included was because it was found or provided. Our final prototype is at the top of this page.
![Bill of Materials]({{ "/assets/images/selfsift-bom.jpg" | relative_url }}){: .inline-image-1 style="width: 575px"}