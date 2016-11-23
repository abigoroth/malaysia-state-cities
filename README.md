# Malaysia

Database for Malaysian states and cities.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'malaysia'
```

And then execute:

```
$ bundle
```

Or manually install

```
$ gem install malaysia
```

##Usage

**Listing states**
```ruby
Malaysia.states
 => ["Selangor", "Johor", "Sabah", "Kuala Lumpur", "Kedah", "Kelantan", "Melaka", "Negeri Sembilan", "Pahang", "Penang", "Perak", "Perlis", "Putrajaya", "Sarawak", "Terengganu"]
  ```

**Listing cities by state**
 ```ruby
Malaysia.cities['Selangor']
 => ["All", "Alam Impian", "Aman Perdana", "Ambang Botanic", "Ampang", "Ara Damansara", "Balakong", "Bandar Botanic", "Bandar Bukit Raja", "Bandar Bukit Tinggi", "Bandar Kinrara", "Bandar Puncak Alam", "Bandar Puteri Klang", "Bandar Puteri Puchong", "Bandar Saujana Putra", "Bandar Sri Damansara", "Bandar Sungai Long", "Bandar Sunway", "Bandar Utama", "Bangi", "Banting", "Batang Berjuntai", "Batang Kali", "Batu Arang", "Batu Caves", "Beranang", "Bukit Jelutong", "Bukit Rahman Putra", "Bukit Rotan", "Bukit Subang", "Cheras", "Country Heights", "Cyberjaya", "Damansara Damai", "Damansara Intan", "Damansara Jaya", "Damansara Kim", "Damansara Perdana", "Damansara Utama", "Denai Alam", "Dengkil", "Glenmarie", "Gombak", "Hulu Langat", "Hulu Selangor", "Jade Hills", "Jenjarom", "Kajang", "Kapar", "Kayu Ara", "Kelana Jaya", "Kerling", "Klang", "Kota Damansara", "Kota Emerald", "Kota Kemuning", "Kuala Kubu Baru", "Kuala Langat", "Kuala Selangor", "Kuang", "Mutiara Damansara", "Nilai", "Petaling Jaya", "Port Klang", "Puchong", "Puchong South", "Pulau Indah ( Pulau Lumut)", "Pulau Carey ", "Pulau Ketam", "Puncak Jalil", "Putra Heights", "Rasa", "Rawang", "Sabak Bernam", "Saujana", "Sekinchan", "Selayang", "Semenyih", "Sepang", "Serdang", "Serendah", "Seri Kembangan", "Setia Alam", "Setia Eco Park", "Shah Alam", "SierraMas", "SS2", "Subang Bestari", "Subang Heights", "Subang Jaya", "Sungai Ayer Tawar", "Sungai Besar", "Sungai Buloh", "Sungai Pelek", "Taman Melawati", "Taman TTDI Jaya", "Tanjong Karang", "Tanjong Sepat", "Telok Panglima Garang", "Tropicana", "Ulu Klang", "USJ", "USJ Heights", "Valenci"]
  ```

## Contributing

Bug reports and pull requests are welcome .

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
