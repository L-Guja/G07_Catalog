﻿დამიწერეთ სერვისი, რომელიც მომცემს საშუალებას წავიკითხო
პროდუქციის სია, კატეგორიის მიხედვით.

ჩვენ უნდა გვქონდეს 2 EndPoint:
1) http://localhost:5041/Categorys
ამან უნდა დაგვიბრუნოს ყველა კატეგორია.
პასუხში უნდა იყოს ID და Name ველები.
2) http://localhost:5041/Products/{categoryid}
ამან უნდა დაგვიბრუნოს ყველა პროდუქტი მითითებულ კატეგორიაზე.
უნდა დაბრუნდეს პროდუქტის ყველა ველი.
მაგ. http://localhost:5041/Products/1 ამან უნდა დააბრუნოს 
კატეგორია 1-ის ყველა პროდუქტი.

ბაზასთან წვდომა გააკეთეთ ცალკე ბიბლიოთეკაში EF-ით.

შეეცადეთ გატესტოთ Postman-ით.