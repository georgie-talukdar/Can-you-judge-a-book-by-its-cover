# Data Descriptions 
## New York Times Data
DOI: https://doi.org/10.18737/CNJV1733p4520220211

nyt_full.tsv - The fiction bestseller list of The New York Times between the years of 1931 and 2020. Each row of the dataset is a single “entry” on the list, that is, a single slot for a single week. Altogether, the dataset features just over 60,000 rows.

* year – the year of appearance
* week – the weekly issue of the bestseller list
* rank – the book’s rank on the list for that week
* title_id – a unique ID mapping titles to the nyt_titles spreadsheet
* title – title of the novel, as reported by the New York Times
* author – author of the novel, as reported by the New York Times

nyt_titles.tsv - Title-level data for every unique title that appears in Lists.

* id – an arbitrary unique id for the novel
* title – the title of the novel, as reported by the New York Times
* author – the author of the novel, as reported by the New York Times
* year – the first year that the novel appears on the bestseller list. Note that this year may be different from the publication year.
* total_weeks – the total number of weeks the title was on the list
* first_week – the first week that the novel appears on the bestseller list
* debut_rank – the book’s bestseller rank in the week of its first appearance
* best_rank – the highest rank achieved by the title while on the list

## Open Library Data
All_Covers - This folder contains all of the covers retrieved from the OpenLibrary using the cover ID's from cover_and_genres

cover_and_genres - Using nyt_titles.tsv cover_id's and genre information have been gathered from the OpenLibrary
* Title - the title of the novel, as reported by the New York Times
* ID - the work id for the novel on the open library website
* Cover - the unique cover id for that edition of the book
* Subjects - the genre of the book as found on the open library website

## Other
merged_df.csv
* Title - the title of the novel, as reported by the New York Times
* ID - the work id for the novel on the open library website
* Cover - the unique cover id for that edition of the book
* Genres (ActionandAdventure,Animals,Art,Children,Contemporary,Crime,Death,Dystopian,Espionage,Family,Fantasy,Fiction,Friendship,Health,Historical,Horror,Humor,Legal,Memoir,Murder,Mystery and Detective,Paranormal,Political,Psychological,Relationships,Romance,Self-help,Suspense,Thriller,Travel,War,Women) - the genre of the book as found on the open library website

* author – the author of the novel, as reported by the New York Times
* year – the first year that the novel appears on the bestseller list. Note that this year may be different from the publication year.
* total_weeks – the total number of weeks the title was on the list
* first_week – the first week that the novel appears on the bestseller list
* debut_rank – the book’s bestseller rank in the week of its first appearance
* best_rank – the highest rank achieved by the title while on the list

