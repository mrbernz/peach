# Notes on Ruby

##objectives
- learn some Ruby
- rejoice
 
```rb
arrays:
arr = []
arr.push("hello")
puts arr - show arr to have hello in it
arr[1]="world"
arr[0]=1
arr.delet_at(1) - delete at index
arr<<"c"<<"d"<<[3,4]
puts arr - show [1, "c","d",[3,4]]
arr [3][0] - show 3
```

```rb
puts "What's your name"
name=gets.chomp
puts "Hello,#{name}, where are you from?"
state = gets.chomp.upcase

if state =="NY"
	puts "Welcome to NY"
elsif state == "NJ"
	puts "You must merge well"
else
	puts "Whaat!"
end
```
###hash:

```rb
hash = {}
hash[:a]=1 - symbol 'a' equals 1
hash = {a:1,b:2}
puts hash - show {:a=>1}
hash = {"a"=>1}
```

- key inside a hash cannot be duplicated
 
```rb
hash.delete(:b)
```

###loops:

```rb
state = "NY"
if state =="NY"
	puts "Welcome to NY"
else
	pus "Where is that?"
end
```

```rb
i=0
while i<0
	puts i
	i+=1
end
```

```rb
numbers = [1,2,3,4,5]
for number in numbers
	puts number
end
```

```rb
hash = {a:1,b:2}
for x in hash
puts "hello #{x}"
end
```

```rb
hash = {a:1,b:2}
for x in hash
	puts "hello #{x[1]}"
end
```

###interpolation

```rb
def generate_welcome_string(name)
	prefix="hello"
	postfix-". Have a nice day"
	welcome_string= prefix + name + postfix or "#{prefix} #{name} #{postfix}"
	return welcome_string
end
```

	
