# README

Main docs are [here](https://quranapi.hashir.pro/docs/)

It supports:

- `/api/chapter/verse/:chapterVerse` ~ Will get a single `verse` by specifying chapter and verse like [`2:32`](https://quranapi.hashir.pro/api/chapter/verse/2:32) i.e. chapter 2 verse 32. This API also supports search inside the verse as well.
- `/api/search/:searchQuery` ~ Will search in the entire Qur'an with your search query. It searches everything including commentary although commentary is not returned in the results to keep responses blazing fast. For example this [link](https://quranapi.hashir.pro/api/search/universe) will search for the keyword **'universe'**.
- `/api/topics` ~ Will get topics and the number of verses per topic sorted by the number of verses per topic. For example this [link]()
- `/api/topic/:topicId` ~ Will get all the verses mentioning the specified topic. For example this [link](https://quranapi.hashir.pro/api/topic/2058) will get all the verses mentioning the topic of **'Prophecies in the Holy Qur’an: about: latter days'**. This API further supports search as well to search for specific keyword **inside** the that topic. For example this [link](https://quranapi.hashir.pro/api/topic/2058?topicId=2058&search=mountains%20are%20blown) will search for the keword(s) **'mountains are blown'** in the topic of **'Prophecies in the Holy Qur’an: about: latter days'**.
- `/api/topics` ~ Will get topics and the number of verses per topic sorted by the number of verses per topic. This API also supports search for specific keyword(s) as well. For example this [link](https://quranapi.hashir.pro/api/topics?search=universe) will return all the topics somewhat related to the keyword **'universe'**.

## Source

All the data that I have extracted is from this [`API`](https://www.alislam.org/quran/read/api.php?action=chapter&v=1:1)
