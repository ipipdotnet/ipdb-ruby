# ipdb-ruby
ruby lang parse ipdb format file

# Installing
<pre>
gem install ipip-ipdb
</pre>

# example
<pre>
db = IPDB.city "c:/work/ipdb/city.ipv4.ipdb"
loc = db.find"1.1.1.1", "CN"
puts loc
<pre>