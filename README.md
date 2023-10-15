tojavascript-
dateconst. http =
 require
('1http0');. Mon
itor
 yourconst server website =' https. performancecreate:Server To(( ensurereq that, your website res) => {
 res.statusCode = 200;
 res.setHeader('Content-Type', 'text/plain');
 res.end('Hello World');
});

server.listen(3000, () => {
 console.log('Server running at http://localhost:3000/');
});

