# Smart data center cooling

One percent of world’s power is consumed by data centers, just to cool themselves. Though data centers use best in class air conditioning, these systems don’t capture a holistic picture of the thermal environment and end up over-cooling, by a whole lot of **35%.** That was a wastage of **11 billion dollars** in 2019, projected to increase at **20%** every year.

With an expertise ranging from managing thermal environments of worlds most complex aero-engines to using machine learning to make systems that learn from and operate on the real world, we aim to manage thermal environments using a system that dynamically controls cooling hardware and learns from its behaviors over time.

### Rapid DC Growth in India

Average Power Usage Effectiveness (PUE) of Data Centers (DCs) across India is [1.7](https://www.osti.gov/servlets/purl/1249186), and since most of them use best-in-class Heating, Ventilation and Air Conditioning (HVAC) systems, there is little that can be done using hardware mods to make cooling in data centers more efficient. On the contrary, with a compound annual growth rate (CAGR) predicted at [20%](https://www.datacenterdynamics.com/en/analysis/indias-data-centers-are-set-growth/), 25 new DCs are built every year (each with an average rack power density of around [8-10 kW](http://bwcio.businessworld.in/article/India-Data-Center-Market-2019-2024/06-02-2019-166872/)) and it is imperative for DCs to look for opportunities to improve their PUE numbers to make the most out of available equipment and have a competitive edge.

### We reduce DC cooling energy costs by 40-50% using machine learning

Our company offers one such opportunity. We aim to understand your current DC architecture and save your DC cooling energy costs by 40-50% using machine learning. With recent advances in machine learning and artificial intelligence, and with [Google](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/bb67802995f7af4c6ba948ede1acfc8756be7134.pdf) having already tried applying reinforcement learning to optimise its DC cooling, we are working to make it possible for our software to understand your DC structure (the equipment you chose to install, the location you chose to set your DC in, the time of the day you want your DC to run most efficient) and cool your DC as needed using as little energy as possible. Our solution is software only and doesn’t require any modifications to hardware of your DCs.

### Heat Transfer meets Machine Learning

We are a team of 2 passionate engineers focused on developing applications that help organisations reduce energy consumption. My co-founder, [Apurva Gupta](https://www.linkedin.com/in/apurva-gupta-74229a30/) is a Mathematics and Computing graduate from IIT Kanpur with expertise in machine learning. I, [Vaibhav Rao](https://www.linkedin.com/in/vaibhavraov/), am a Computational Heat Transfer and Fluid Mechanics post-graduate from BITS Pilani with experience in simulating and optimising thermal environments of Rolls-Royce aero-engines. Together, with our combined expertise, we are looking forward to providing solutions that reduce energy consumption.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
