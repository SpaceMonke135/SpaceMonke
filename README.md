data:text/html;charset=utf-8,data%3Atext%2Fhtml%2C%20%3Cscript%20src%3D'https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fdragon731012%2Fcaudns%2Fjszip.js'%20defer%3E%3C%2Fscript%3E%20%3Cscript%20src%3D'https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fdragon731012%2Fcaudns%2Ffilesaver.js'%20defer%3E%3C%2Fscript%3E%20%3Cscript%20src%3D'https%3A%2F%2Fcaudns.vercel.app%2Fmain.js'%20defer%3E%3C%2Fscript%3E%20%3Cscript%3E%20function%20getHtml(file)%7B%20return%20new%20Promise((resolve)%20%3D%3E%20%7B%20fetch(file)%20.then((response)%20%3D%3E%20%7B%20return%20response.text()%3B%20%7D)%20.then((html)%20%3D%3E%20%7B%20resolve(html)%3B%20%7D)%3B%20%7D)%3B%20%7D%20async%20function%20start()%7B%20var%20html%3Dawait%20getHtml('https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fdragon731012%2Fcaudns%2Fdata.txt')%3B%20html%3Dhtml.toString()%3B%20console.log(html)%3B%20document.body.innerHTML%3Dhtml%3B%20%7D%20start()%3B%20%3C%2Fscript%3E
