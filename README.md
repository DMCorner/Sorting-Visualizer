
# Sorting Visualizer Site
A website I've built to show Merge, Heap, Quick and Bubble sort working on a randomised array of length 100, constructed with create-react-app.

# Lessons Learned
My first React project, while difficult to learn the basics of react while implementing the algorithms I enjoyed the challenge.

I needed to learn a lot about how the virtual DOM works and how to properly update it. As a side I also learned about big O notation though I'm unsure about how relevant that is within front end development.

# Potential Future Features
1) A slider that varies the time between the steps of the sorting algorithm. Bubble sort takes a bit too long while quick sort is too fast to really see how it works.

2) Import specific arrays. While my app likely wouldn't be the optimal way to sort arrays this feature would at least increase its utility.

3) Not allow multiple algorithms to run on the same array. Most obvious if bubble sort is clicked twice but a user can have multiple algorithms running at the same time. This is a just a bug that looks strange. It can be easily fixed by hiding the buttons after one has been pressed but there may be a more elegant solution.

# Deployment
Deployed with vercel. https://sortvis-ebon.vercel.app/
