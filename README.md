# IDS706Pj6-NLP

Project #6: Small Data Engineering NLP and AI APIs with “No Code/Low Code” [General]

* Scrape all of Hemingway’s writing from this website (or some other author): http://gutenberg.ca/index.html (Can be manual or with Python)
* Create Data Visualization summarizing what you learned.
* Create one-page in report, in Github using Markdown summarizing the point of the data visualization (give firm recommendation/conclusion)
* Example Walkthrough Video: https://learning.oreilly.com/videos/no-code-and/62202021VIDEOPAIML/
* Example Repo: https://github.com/noahgift/exploratory-data-analysis

## Introduction
This analysis uses six of Hemingway's novels. All the novels were acquired from the Gutenberg website, and the list is as follows.
* The Sun Also Rises (1926)
* Men Without Women (1927)
* Winner Take Nothing (1933) 
* Green Hills of Africa (1935)
* Across the River and Into the Trees (1950)
* The Old Man and the Sea (1952)

## Word Cloud
A word cloud is a visual representation of words. Cloud creators are used to highlight popular words and phrases based on frequency and relevance. They provide us with quick and simple visual insights that can lead to more in-depth analyses.

* The Sun Also Rises
![sun_cloud](https://user-images.githubusercontent.com/90014065/144721344-8fea798a-dd53-4a2f-8dc1-76d800061a48.png)

* Men Without Women
![men_cloud](https://user-images.githubusercontent.com/90014065/144721342-966df134-58cf-4aa3-97a6-6a07b60ceae7.png)

* Winner Take Nothing
![winner_cloud](https://user-images.githubusercontent.com/90014065/144721347-9abe4cc5-2b1a-415c-a045-705be027a5fa.png)

* Across the River and Into the Trees
![river_cloud](https://user-images.githubusercontent.com/90014065/144721336-16beab77-280e-4e3b-8f77-b236b652f689.png)

* Green Hills of Africa
![green_cloud](https://user-images.githubusercontent.com/90014065/144721341-3ba03f5c-5998-4c8a-98a6-4d15af53b3e8.png)

* The Old Man and the Sea
![old_cloud](https://user-images.githubusercontent.com/90014065/144721343-d2c82f7e-9f06-40dc-a9f3-68e18de012db.png)

## Word Frequency Chart using AWS QuickSight
We can easily create charts using AWS QuickSight. Made a bar chart according to the frequency of the most used words in each novel.

* The Sun Also Rises
![Sun](https://user-images.githubusercontent.com/90014065/144721592-71ff3273-3310-4085-9ac6-3a269cec74f2.png)

* Men Without Women
![Men](https://user-images.githubusercontent.com/90014065/144721586-b93c0e4f-3554-4eab-97ed-685a076db83b.png)

* Winner Take Nothing
![Winner](https://user-images.githubusercontent.com/90014065/144721594-8a8780bc-daf4-4928-b523-f99e9307a79f.png)

* Across the River and Into the Trees
![River](https://user-images.githubusercontent.com/90014065/144721588-6a4e3356-42e9-4e6c-8d8d-0d2c48b78d31.png)

* Green Hills of Africa
![Green](https://user-images.githubusercontent.com/90014065/144721584-19581032-6ca8-42ed-952f-789ecc0807c5.png)

* The Old Man and the Sea
![Old](https://user-images.githubusercontent.com/90014065/144721587-dd83e96b-9b6a-41b4-9048-730ea10c090d.png)

## Image Recognition using AWS Rekognition
We can use AWS Rekognition to recognize images. When I uploaded an image of a book I had downloaded from Wikipedia, AWS recognized what kind of object this image was and informed me. AWS also read the text of book covers. The recognition rate was not perfect, but it was very high and reliable.

* The Sun Also Rises
![Sun_label](https://user-images.githubusercontent.com/90014065/144722172-2ddda668-ace1-4d9a-b6fe-afc915d32619.png)
![Sun_text](https://user-images.githubusercontent.com/90014065/144722174-f1fc83ad-ed74-4e87-a439-ed751920193c.png)

* Men Without Women
![Men_label](https://user-images.githubusercontent.com/90014065/144722154-7ab1f84e-9fbc-4099-8d72-e77ed97ac2a8.png)
![Men_text](https://user-images.githubusercontent.com/90014065/144722159-01c99a8e-d259-469d-9cee-3c12dc296d62.png)

* Winner Take Nothing
![Winner_label](https://user-images.githubusercontent.com/90014065/144722176-38c2ae1d-778a-408e-babd-3932b73f6b84.png)
![Winner_text](https://user-images.githubusercontent.com/90014065/144722177-d33ae5f1-68da-4fd5-980d-90bf7d15773f.png)

* Across the River and Into the Trees
![River_label](https://user-images.githubusercontent.com/90014065/144722168-0bb9f755-6e01-49ef-ac32-15e76b288f25.png)
![River_text](https://user-images.githubusercontent.com/90014065/144722171-785491cf-8c07-4145-a067-c96d50306d61.png)

* Green Hills of Africa
![Green_label](https://user-images.githubusercontent.com/90014065/144722147-bfa45574-5acc-4aa0-8931-73bd84d14ac6.png)
![Green_text](https://user-images.githubusercontent.com/90014065/144722150-065290d2-7e6a-4ec0-8987-428e6555c5ee.png)

* The Old Man and the Sea
![Old_label](https://user-images.githubusercontent.com/90014065/144722161-2336cfe2-018b-428b-ad07-006a3d9e09b7.png)
![Old_text](https://user-images.githubusercontent.com/90014065/144722165-bb5f7cc0-4f71-40c6-8912-c6ef9f3b914c.png)
