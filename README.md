# JSON 3D Graph Visualizer
_Connecting your ideas visualizing them better._

<img style="text-align: center;" width="671" height="534" alt="image" src="https://github.com/user-attachments/assets/0849573f-bc16-49c2-a7f3-84e0946d0654" />

## Motivation

I wanted to visualize words and concepts quickly. No Markdown files only to visualize itens on a graph; I was looking for making mental maps in 3D, "connecting the dots" in a way that I could see only by carrying my laptop/phone with me.

Sometimes lists are way too rigid and do not show how concepts, ideas or data are linked to each other.

This visualizer stores words as **JSON objects** that **can be connected to N other objects**, treating each little content as a **node**. This way, you can link keywords, texts, concepts and branch your thinking - and display it even better. Sometimes a picture is worth a thousand words; and this 3D visualizer is worth a thousand lists.

SQL Tables? School classes concepts? Family trees? Bridging divergences? Helping an audience understand better your lectures? You come with the goal, the visualizer sets the stage and shows it. Beautifully.

## Features

- _No database required_. Everything is stored in your machine as a JSON file and you can save it and load it again.
- _Pleasant UI_. You will be amazed by how it looks.
- _No internet required_. Download the HTML and open it in your browser. It works.
- _Customize the view_ by changing node colors.
- _View your ideas from new perspectives_: you can drag, rotate, zoom-in and zoom-out your visualization.
- [NEW] _Image nodes_: insert images to connect them into concepts.

## Usage

1. Download index.html into your device.
2. Open it with your go-to browser.
3. At the left side, there is a form like this:

<img width="236" height="347" alt="image" src="https://github.com/user-attachments/assets/82e0e7b0-b486-48f5-9738-2b6f53c74be7" />

5. Fill it and click on _Save node_.
6. It will appear on the visualization window at the page's body:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c6a46983-937e-4ea7-951a-6dc9ebf6bdc8" />

7. If you create another one, it will pop there too:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e2ee6c6d-2e90-4882-a215-49d4a2bf7b2b" />

8. Click on a node, then click on the other node and hit _Save node_:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1b646b0c-7f16-4351-8369-e8090f27bc64" />

9. Boom! They are connected.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/eb7a570b-42bf-4e5b-be9b-ed8f210acc1b" />

10. You can save your node net by clicking on _Save JSON_ on the top right corner. This modal will pop up:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0621f613-0de2-4e3a-840d-e1e12107645c" />

11. Copy it and save as a JSON file in your local machine.

12. When you want to load your node net, click on _Import JSON_ and paste the JSON file content that has your node net:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ab23127c-7841-4c1b-92f6-d9d4007ba34e" />

14. It will load the node net instantly into your screen!

15. Clicking on a node will re-center your view window to that node.

## Next goals

- Improve even more UI by changing ball-style nodes to rounded-square with labels that can expand its content.
- Turn its design mobile-friendly (responsiveness).
- Tweaking node movement when recently added.
- Changing "selected" and "connected" color indicators to glow-like effects, allowing color customization to look better in those modes.
- Displaying nodes as title with expandable content when clicked twice.
- Right-click + drag will allow X-Y-axis movement without rotating the view.
- Video rendering inside nodes by using YouTube iframes.
- Nodes that are links to other documents online (PDFs, articles).
- (more? Give us a suggestion by opening an issue!)
