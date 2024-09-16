# katalon-taskAPI-WulanSari

Pertama, buat object repository untuk masing-masing endpoint dari baseUrl https://jsonplaceholder.typicode.com.

	GET: /posts
	POST: /posts
	PUT: /posts/5
	DELETE: /posts/5

Lalu, buat test casenya menggunakan object repository yang sudah dibuat.
Setelah dipastikan test case-nya sudah passed semua, baru buat test suite-nya.
Setelah run test suite-nya, akan tergenerate report.

Ada 2 report dari 2 test suites:
1. Test suite "Posts"
   Terdiri dari 4 test cases (get posts, post a post, put a post, delete a post). 

3. Test suite "Etc"
   Terdiri dari test cases selain "posts" (get comments, get albums, get photos, get todos). 
