## Publisher



### IEEE

```bash
(("Metadata": "elearning" OR
"Metadata": "e-learning" OR
"Metadata": "digital learning")
AND
(NOT
("Metadata": "mooc" OR
"Metadata": "moocs" OR
"Metadata": "Massive Open Online Course")))

OR

(("Document Title": "elearning" OR
"Document Title": "e-learning" OR
"Document Title": "digital learning")
AND
(NOT
("Document Title": "mooc" OR
"Document Title": "moocs" OR
"Document Title": "Massive Open Online Course")))

OR

(("Author Keywords": "elearning" OR
"Author Keywords": "e-learning" OR
"Author Keywords": "digital learning")
AND
(NOT
("Author Keywords": "mooc" OR
"Author Keywords": "moocs" OR
"Author Keywords": "Massive Open Online Course")))

OR

(("Abstract": "elearning" OR
"Abstract": "e-learning" OR
"Abstract": "digital learning")
AND
(NOT
("Abstract": "mooc" OR
"Abstract": "moocs" OR
"Abstract": "Massive Open Online Course")))
```

*OR*

```bash
(("Metadata": "elearning" OR
"Metadata": "e-learning" OR
"Metadata": "digital learning")
AND
(NOT
("Metadata": "mooc" OR
"Metadata": "moocs" OR
"Metadata": "Massive Open Online Course")))

OR

((title: "elearning" OR
title: "e-learning" OR
title: "digital learning")
AND
(NOT
(title: "mooc" OR
title: "moocs" OR
title: "Massive Open Online Course")))

OR

((authorTerms: "elearning" OR
authorTerms: "e-learning" OR
authorTerms: "digital learning")
AND
(NOT
(authorTerms: "mooc" OR
authorTerms: "moocs" OR
authorTerms: "Massive Open Online Course")))

OR

((documentAbstract: "elearning" OR
documentAbstract: "e-learning" OR
documentAbstract: "digital learning")
AND
(NOT
(documentAbstract: "mooc" OR
documentAbstract: "moocs" OR
documentAbstract: "Massive Open Online Course")))
```

> **& manual filtering according to the corresponding year for the publication date, since automatic filtering via the search querie is not possible so far.**





### ACM

```bash
[[[Publication Title: "elearning"] OR
[Publication Title: "e-learning"] OR
[Publication Title: "digital learning"]]
AND
[NOT
[[[Publication Title: "mooc"] OR
[Publication Title: "moocs"] OR
[Publication Title: "Massive Open Online Course"]]]]]

OR

[[[Keywords: "elearning"] OR
[Keywords: "e-learning"] OR
[Keywords: "digital learning"]]
AND
[NOT
[[[Keywords: "mooc"] OR
[Keywords: "moocs"] OR
[Keywords: "Massive Open Online Course"]]]]]

OR

[[[Abstract: "elearning"] OR
[Abstract: "e-learning"] OR
[Abstract: "digital learning"]]
AND
[NOT
[[[Abstract: "mooc"] OR
[Abstract: "moocs"] OR
[Abstract: "Massive Open Online Course"]]]]]

AND

[E-Publication Date: (01/01/2000 TO 12/31/2000)]
```

*OR*

```bash
((ContentGroupTitle:("elearning") OR
ContentGroupTitle:("e-learning") OR
ContentGroupTitle:("digital learning"))
AND
(NOT
(ContentGroupTitle:("mooc") OR
ContentGroupTitle:("moocs") OR
ContentGroupTitle:("Massive Open Online Course"))))

OR

((Keyword:("elearning") OR
Keyword:("e-learning") OR
Keyword:("digital learning"))
AND
(NOT
(ContentGroupTitle:("mooc") OR
ContentGroupTitle:("moocs") OR
ContentGroupTitle:("Massive Open Online Course"))))

OR

((Abstract:("elearning") OR
Abstract:("e-learning") OR
Abstract:("digital learning"))
AND
(NOT
(ContentGroupTitle:("mooc") OR
ContentGroupTitle:("moocs") OR
ContentGroupTitle:("Massive Open Online Course"))))
```


ContentGroupTitle:("elearning") AND ContentGroupTitle:(NOT moocs) AND
Keyword:(elearning) AND Keyword:(NOT moocs) AND Abstract:(elearning) AND Abstract:(NOT moocs)




### Elsevier

```bash
("elearning" OR
"e-learning" OR
"digital learning")

AND

(NOT
("mooc" OR
"moocs" OR
"Massive Open Online Course")
)
```

> **& manual filtering according to the corresponding year for the publication date, since automatic filtering via the search querie is not possible so far.**





### ~~Springer~~

```
> A detailed search is not possible at Springer at the moment (date of the paper). <
```