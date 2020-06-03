# effiorg

Tor exit relay settings and notice website.

Website and Tor exit relay [tor.effi.org](http://tor.effi.org/).

- Example torrc
- Example index.html

One page combines all images and CSS styles inside one HTML document.
Images converted as base64 data/text.

```sh
sudo apt-get -y install tor
sudo apt-get -y install haveged

sudo cp torrc /etc/tor/torrc
sudo cp index.html /etc/tor/
sudo service tor reload
```
