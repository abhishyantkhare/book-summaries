## Automatic Book Summaries
Most work in text summarization has revolved around summarizing _short_ documents, such as articles or papers. However, books remain an important way that information is disseminated. Human made summaries of books have been incredibly important - ask anyone who has ever used Sparknotes to pass a Shakespeare reading quiz. Books in particular can benefit from summaries because they spend a lot of time diving into details, going over multiple examples, and spend time attempting to clarify a point. However, for anyone just wanting to get the main points from a book, it can be efficient to read a summary instead. This project attempts to create a neural network to automatically summarize books. I'm going to start with a LSTM encoder decoder structure, and improve upon it from there.

Data:
* The book text itself comes from Project Gutenberg, an incredibly valuable resource that provides free books: https://www.gutenberg.org
* The plot summaries come from the CMU corpus collected by David Bamman: http://www.cs.cmu.edu/~dbamman/booksummaries.html
