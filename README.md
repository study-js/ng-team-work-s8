გააკეთეთ წიგნების შეკვეთს საიტის აპლიკაცია (single page application)

აუცილებელია იყოს შემდეგი გვერდები:

store/books - უნდა გამოდიოდეს წიგნები სიის სახით (პატარა სურათი + მოკლე დასახელება)

კონკრეტული წიგნის დათვალიერების გვერდი

/store/books/id

უნდა გამოდიოდეს კონკრეტული წიგნის შესახებ ინფორმაცია: დიდი სურათი, და მახასიათებლები ცხრილის სახით

/admin/books - წიგნების სია დამატების, წაშლის და რედაქტირების ღილაკებით

/admin/books/id/edit - კონკრეტული წიგნის ინფორმაციის რედაქტირებისთვის

/admin/books/new - ახალი წიგნის დამატების ფორმა

ყველა ajax request-ის შესრულებისას უნდა გამოჩნდეს spinner-ი

აუცილებელია სერვისების გამოყენება

ბექენდის მაგივრად გამოიყენეთ https://github.com/typicode/json-server
