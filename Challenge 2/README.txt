The first was obtain an API key to consume the resurces from http://developer.marvel.

Then I consumed the resource from https://gateway.marvel.com:443/v1/public/characters?name=Deadpool&apikey=c3773e9d5f6fbf3b3edbd60226be1df9 to
obtain information about Deadpool.

Later I consumed the resource from https://gateway.marvel.com:443/v1/public/comics?title=Cable%20%26%20deadpool&issueNumber=46&apikey=c3773e9d5f6fbf3b3edbd60226be1df9, where I obtained the ID of Cable & Deadpool (2004) #46 (Zombie Variant)
With this ID then, I could search at endpoint https://gateway.marvel.com:443/v1/public/comics/21845/characters?apikey=c3773e9d5f6fbf3b3edbd60226be1df9 where It returned to me the list of all characters from this specific commic with a little description of Them.

Finally I searched Agent X (Nijo) id and with this I could find all stories where he appears.


PD: I used developer.marvel to obtain the JSONs but i could bring information back with "curl" too, but first i had to find a hash for consume the resource

 