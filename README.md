# Sort-Viz

This project aims to provide an interactive platform for visualizing various sorting algorithms in action. Users can generate arrays of elements and choose from a selection of sorting algorithms to observe their behavior in real-time. The project integrates concepts learned during the DSA course, including arrays, sorting algorithms, and interactive visualization techniques.This project aims to provide an interactive platform for visualizing various sorting algorithms in action. Users can generate arrays of elements and choose from a selection of sorting algorithms to observe their behavior in real-time. The project integrates concepts learned during the DSA course, including arrays, sorting algorithms, and interactive visualization techniques.

## The algorithm used are: 

### Bubble Sort

Imagine playing a game where you compare two socks next to each other. If the colors are wrong (e.g., blue next to red), you swap them. You keep repeating this process throughout the drawer, moving the "correctly colored" socks towards the front. Eventually, all the socks will be sorted – just like bubbles rising to the top! This is a simple and easy-to-understand method, but it becomes quite slow when dealing with a large drawer full of socks (or a massive dataset).

### Insertion Sort

Picture yourself lining up your friends by height. This sorting method works similarly. Start with an empty "line" (a sorted sub-list) and pick a sock from the drawer. Find the correct spot for that sock in the line based on its color (compared to the socks already there). You keep inserting socks one by one, maintaining a sorted order as you go. This method works well if some of your socks are already partially sorted (like having pairs close together).

### Selection Sort

This method is like picking the "lone sock" out of a pair. You scan the drawer, looking for the sock with the odd color (the smallest or largest, depending on how you want to sort). Once you find it, you move it to the front of the drawer. Then, you repeat the process, finding the next "odd sock" among the remaining ones. This continues until all the socks are paired up (sorted) in the drawer. While simpler than Bubble Sort, it's still not ideal for huge piles of socks


### Merge Sort

Imagine you have a huge pile of socks to sort. Merge Sort helps you tackle it by splitting the pile in half. You then sort each half individually (like sorting two smaller drawers). Once both halves are sorted, you carefully merge them back together, comparing colors and placing socks in the right order until the entire pile is sorted. This "divide and conquer" approach makes it a faster option for large datasets.


### Heap Sort 

Imagine building a sandcastle, but instead of using the biggest block first, you keep taking the biggest remaining block to build it. This way, the biggest blocks end up at the bottom. Sorting works similarly here. We create a special data structure called a "heap" (think of it as a messy pile of socks with a specific order). The "biggest" sock (largest number) is always at the top. We keep removing this top sock (which is now sorted) and rebuilding the heap with the remaining socks. This process continues until all the socks are removed and sorted in descending order (the biggest ones at the bottom, just like our sandcastle!).

### Quick Sort

 This method is a bit like picking a team captain for your sock sorting game. You choose any sock as a "leader" and compare all the other socks to it. Socks with a color "shorter" than the leader's (smaller number) go to one side, and "taller" ones (larger numbers) go to the other. Now, you have two smaller piles! You repeat the process of picking a leader and sorting each side separately. Finally, you combine the sorted piles to get the entire drawer sorted. This can be a very fast sorting method on average, but sometimes it can take longer, depending on the choice of the leader.

 ## Array Before Sorting
 <center><img src="New Array Generated.png" align="center" height="350"></center>
 
 ## Array After Sorting
 <center><img src="Sorted Array.png" align="center" height="350"></center>
