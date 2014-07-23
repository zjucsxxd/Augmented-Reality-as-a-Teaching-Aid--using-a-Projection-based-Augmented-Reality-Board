Augmented-Reality-as-a-Teaching-Aid--using-a-Projection-based-Augmented-Reality-Board
=====================================================================================

I designed and implemented a tangible game interface using projector-camera systems. The system offers a simple and quick setup and economic design. The projection onto a paper board held by the user provides more direct viewing as well as more natural and flexible interaction than bulky HMD’s or monitor-based game interfaces. Homography calibration techniques are used to provide geometrically compensated projections on the board with robustness and accuracy. With the prevalence of low-cost projectors and cameras, more and more projector based entertainment systems come into existence. Traditional displays such as CRT monitors and LCD panels are limited by their display size and heavy weight. For large-scale display walls, projectors provide better display quality compared to screens because of the lack of physical seams. However, entertainment activities involving projectors are usually watching movies, playing video games, etc. which only exploit the projector’s characteristics in creating large displays. Cameras, if combined with projectors, can enable an intelligent projection system to project certain content and “see” it at the same time. This empowers a projector-camera system to support more complex interactions with the virtual and real world. A projector’s capability of projecting images onto objects or surfaces, combined with a camera’s capability of seeing the objects and surfaces, enables the use of projector-camera systems in a variety of augmented reality applications.
Game Logic
We designed our game logic in with openFrameworks. It is a Quiz Application with five subjects namely English, Science, Geography, Biology and Math. The logic is very simple, each subject is divided into beginners, intermediate and advanced. Each level has 25 questions.
When the user clicks the right answer: CORRECT is displayed and the user clicks the wrong answer: WRONG is displayed. The whole interaction is by a Laser Pointer.
