This package is a thin wrapper around the Unpaywall API from Our Research, with some convenience functions. It makes it easier to download open-access papers programmatically.

Use:

Open-access information on a paper, based on the doi
```
>>>import unpaywallpython
>>>unpaywallpython.email = "myemail@gmail.com"
>>>doi="10.1038/s41408-020-0288-3"
>>>oa_info = unpaywallpython.unpaywall_json(doi)
```

Links to open-access copies of a paper
```
>>>unpaywallpython.unpaywall_all_links(doi)
```
