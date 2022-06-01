###Commands

###set env variable
```bash
export TODO_FILENAME=new-todo.json
```

###post todo 
```bash
./todo -add Including item from Args
OR
echo "Learn go" | ./todo -add
```

###return the list
```bash
go run main.go -list
```

### no arguments will return todo list
```bash
go run main.go 
```

### view json file 
```bash
cat new-todo.json
```

### delete json file
```bash
rm .todo.json
```

### unset file name
```bash
unset TODO_FILENAME
```



##TODO: implement delete and complete functionality
