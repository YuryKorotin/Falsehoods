## Awesome falsehoods 

### Falsehoods programmers believe about names

> * People's names do not change
> * My system will never have to deal with names from China
> * I can safely assume that this dictionary of bad words contains no people’s names in it
> * People have names	

### Falsehoods programmers believe about time

> * The time zone in which a program has to run will never change
> * The system clock will never be set to a time that is in the distant past or the far future
> * One minute on the system clock has exactly the same duration as one minute on any other clock
> * A time stamp of sufficient precision can safely be considered unique
> * The duration of one minute on the system clock would never be more than an hour

### Falsehoods programmers believe about geography

> * Places have only one official name
> * Places have only one official name per language
> * Place names follow the character rules of the language
> * Place names can be written with the usual character set of a country
> * Places have only one official address
> * Countries have capitals
> * Buildings do not move
> * Street adresses contain street names
> * Language codes will match the country code of the country they are associated with

### Falsehoods programmers believe about names

> * An address will start with, or at least include, a building number.
> * When there is a building number, it will be all-numeric.
> * No buildings are numbered zero.
> * Well, at the very least no buildings have negative numbers.
> * We can put those funny numbers into the building name field, as no buildings have both a name and a funny number.
> * When there's a building name, there won't be a building number (or vice-versa).
> * A building number will only be used once per street.
> * When there's line with a number in an address, it's the building number.
> * A building will only have one number.
> * The number of buildings is the difference between the highest and lowest building numbers.
> * If the addresses on the left of the road are even, the addresses on the right must be odd.
> * A building name won't also be a number.
> * You can omit leading zeros.
> * A street name won't include a number.
> * Numbers in street names are expressed as words, not digits.
> * When there's a numbered street and a house number, there will be a separator between them.
> * When addresses do have a descriptor there will only be one.
> * Addresses do have a descriptor it will be at the end.
> * You wouldn't name a town Street.
> * Street names don't recurr in the same city.
> * Street names don't recurr in close proximity.
> * An address will be comprised of road names.
> * A road will have a name.
> * A road will only have one name.
> * Addresses will only have one street.
> * Addresses will have a street.
> * An address will include a state.
> * Addresses will have something other than the organisation and city name.
> * An address will have a county.
> * An address require both a city and a country.
> * You can't have two towns cities with the same name in the same country.
> * Customers will have a fixed address with a fixed location.

### Falsehoods programmers believe about map

> * All coordinates are in latitude/longitude.
> * If you know the latitude/longitude you can be certain of exactly where you are.
> * Spatial is special.
> * The earth is round.
> * The earth is ellipsoidal.
> * The GPS-satellites know where I am.
> * There is a single, right, map projection.
> * Scale numbers works on a screen.
> * There are no good alternatives to Google Maps.
> * Web Mercator works for all purposes.
> * The shortest path between two points is a straight line.
> * All programmers agree on the ordering of latitude and longitude pairs.
> * Given a paper map I can always digitize and georeference it.
> * My background map will be better if I cache it, always!.
> * GIS software is always expensive.
> * The whole world is mapped, thouroughly.
> * Looking up a street address and get it’s position is easy.
> * Offline maps is as easy as Goole Maps.

### Falsehoods programmers believe about language

> * Translating my application into other languages isn’t important
> * Translating a single word of English is simple.
> * Short words in English are short in other languages.
> * Translating a whole sentence of English is simple.
> * Templating sentences adds only a little complexity.
> * If I make sure to group things like articles in with nouns, that’ll sort gendered languages.
> * I can write enough grammatical metadata to be able to stitch together coherent sentences in all the languages I’m targeting.
> * If I allow for two versions of every English sentence, I’ll be OK for gendered languages.
> * At least templating users’ names in is safe.
> * I can reword my copy to avoid these kinds of pitfalls.

### Falsehoods programmers believe about network

> * Data on the network cannot be altered.
> * Encrypted data on the network cannot be altered.
> * Data cannot be accidentally corrupted, because TCP has checksums and Ethernet has CRCs
> * it's inside my perimeter firewall, that means I have total control over it.
> * If it doesn't return an error, then send() sent all the data that was asked of it.
> * Packets arrive in the order in which they were sent.
> * Segment boundaries on a TCP stream are meaningful to the application.
> * Segment boundaries on a TCP stream are not meaningful to the application.
> * If you can't ping the target, then it doesn't exist.
> * If you can ping the target, then it does exist.
> * TCP RSTs come from end-nodes.
> * Bytes must be "swapped" from the network byte-order to the host CPU byte-order.
> * It's an internal web app -- outsiders won't be able to discover where it is.
> * The DHCP address will be the same after a reboot.
> * The DHCP address will remain the same until the next reboot.
> * Well, it'll last a long time between changes
> * Packets/PDUs go up or down the network stack, never sideways.
> * The IPv4 header is 20 bytes long starting with 0x45 (options are so rare we don't have to worry about them).
> * The DHCP server and local router are the same.
> * There is no IPv6 on my network.
> * NAT automatically blocks all inbound attacks.
> * We know all the devices attached to our network at any given time.
> * VLANs are just as good as physical segmentation.
> * Ok, VLANs aren't as good, but they are good enough for now.
> * We have good WIPS/monitors, so we don't have rogue access-points anywhere.
> * No need to add it to the DNS; I'll remember it.

### Falsehoods programmers believe about phone numbers

> * An individual has a phone number.
> * You can make a call to any phone number.
> * An individual has only one phone number.
> * A phone number uniquelly identifies an individual.
> * Phone numbers cannot be re-used.
> * Phone numbers that are valid today will always be valid.
> * Each country calling code corresponds to exactly one country.
> * A phone number is dialable from anywhere
> * You can send a text message to any phone number.
> * Only mobile phones can receive text messages.
> * There are only two ways to dial a phone number: domestically and from overseas.
> * To make a number dialable, you only need to change the prefix.
> * No prefix of a valid phone number can be a valid phone number.
> * An invalid number will not reach an endpoint.
> * All valid phone numbers follow the ITU specifications.
> * All valid phone numbers belong to a country.
> * Phone numbers contain only digits.
> * Phone numbers are always written in ASCII.
> * Phone numbers have only one prefix at a given time.
> * A leading zero in numbers formatted for domestic usage can always be discarded when dialing from abroad.
> * The country or area code of a phone number indicates the user's location, place of residence, time-zone, or preferred language.
> * The plus sign in front of phone numbers in international format is optional, or can always be replaced by 00.
> * Users will only store phone numbers in your product's phone number fields.
> * Phone numbers are numbers.
> * Phone numbering plans published by governments or telecoms represent reality.

