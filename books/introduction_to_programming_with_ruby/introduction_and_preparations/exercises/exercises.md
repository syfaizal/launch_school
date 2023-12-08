```console
mkdir my_folder
cd my_folder
touch one.rb two.rb
echo 'puts "this is file one"' > one.rb
echo 'puts "this is file two"' > two.rb
ruby one.rb
ruby two.rb
cd ..
mkdir -r my_folder
```