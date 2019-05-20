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

### Falsehoods programmers believe about metric systems

> * There is more than one variant of the metric system.
> * All base SI units are prefix-less.
> * All derived metric units are derived of base SI units.
> * Heterogenous units are of no practical use.
> * Fractional dimensions are of no practical use.
> * Non-metric systems have base units as well.
> * Just as liters has decimeters so that it doesn’t need a numerical proportionality constant, pints has yardsInOneDimensionOfAPint.
> * A gallon is treated much like a liter in their respective systems of measure.
> * All base units are made of base dimensions. 
> * A gallon is a gallon is a gallon. 
> * Written out unit names are not case-sensitive.
> * Base units always reduce to the same derived units.
> * Written out base units should always be presented in the same order.
> * There is no need to differentiate between absolute and relative measurements.
> * Derived unit symbols are represented the same way across systems of measure.
> * All units accepted for use with the SI are base ten.
> * You will never have any namespace issues.

### Falsehoods programmers believe about prices

> * You can store a price in a floating point variable.
> * All currencies are subdivided in 1/100th units (like US dollar/cents, euro/eurocents etc.).
> * All currencies are subdivided in decimal units (like dinar/fils)
> * All currencies currently in circulation are subdivided in decimal units. (to exclude shillings, pennies) (counter-example: MGA)
> * All currencies are subdivided. (counter-examples: KRW, COP, JPY... Or subdivisions can be deprecated.)
> * Prices can't have more precision than the smaller sub-unit of the currency. (e.g. gas prices)
> * For any currency you can have a price of 1. (ZWL)
> * Every country has its own currency. (EUR is the best example, but also Franc CFA, etc.)
> * No country uses another's country official currency as its official currency. (many countries use USD: Ecuador, Micronesia...)
> * Countries have only one currency.
> * Countries have only one currency currently in circulation. (Panama officially uses both PAB and USD)
> * I'll only deal with currencies currently in circulation anyway.
> * All currencies have an ISO 4217 3-letter code. (The Transnistrian ruble has none, for example)
> * All currencies have a different name. (French franc, "nouveau franc")
> * You always put the currency symbol after the price.
> * You always put the currency symbol before the price.
> * You always put the currency symbol either after, or before the price, never in the middle.
> * There's only one currency symbol for any currency. (元, 角, 分 are increasing units of the Chinese renminbi.)
> * For a given currency, you always, but always, put the symbol in the same place.
> * OK. But if you only use the ISO 4217 currency codes, you always put it before the price. (Hint: it depends on the language.)
> * Before the price means on the left. (ILS)
> * You can always use a dot (or a comma, etc.) as a decimal separator.
> * You can always use a space (or a dot, or a comma, etc.) as a thousands separator.
> * You separate big prices by grouping numbers in triplets (thousands). (One writes ¥1 0000)
> * Prices at a single company will never range from five digits before the decimal to five digits after.
> * Prices contains only digits and punctuation. (Germans can write 12,- €)
> * A price can be at most 10^N for some value of N.
> * Given two currencies, there is only one exchange rate between them at any given point in time.
> * Given two currencies, there is at least one exchange rate between them at any given point in time. (restriction on export of MAD, ARS, CNY, for example)
> * And the final one: a standalone $ character is always pronounced dollar. (It's also the peso sign.)

### Falsehoods programmers believe about cars

> * Car has four wheels.
> * If car has more than 4 wheels it's a bus or a truck.
> * Car has one engine.
> * Car has one type of fuel.
> * There is nothing else fuel-related if it's not hybrid.
> * Car consumtion is measured in either metric (l/100km) or imperial (mpg) units.
> * Car height is one value.
> * Hatchbacks have 3 or 5 doors.

### Falsehoods programmers believe about video decoding

> * Decoding is bit-exact, so the decoder used does not affect the quality .
> * Since H.264 decoding is bit-exact, the decoder used does not affect the quality,
> * Hardware decoding means I don not have to worry about perfomance
> * Hardware decoding is always faster than software decoding.
> * A H.264 hardware decoder can decode all H.264 files.
> * A H.264 software decoder can decode all H.264 files.
> * Video decoding is easily parallelizable.

### Falsehoods programmers believe about video playback
> * The display's refresh rate will be an integer multiple of the video file's frame rate.
> * The display's clock will be in sync with the audio clock.
> * I can accurately measure the display's clock.
> * I can accurately measure the audio clock.
> * I can exclusively use the audio clock for timing.
> * I can exclusively use the video clock for timing.
> * My hardware contexts will survive the user's coffee break.
> * My hardware contexts will never disapper in the middle of playback.
> * I can always request a new hardware context after my previous one disappered.
> * It's okay to error and quit if can't request a hardware context.
> * Hardware decoding and video playback will happen on the same device.
> * Transferring frames from one device to another is easy.
> * The user will not notice 3:2 pulldown.
> * The user will not notice the odd dropped or duplicated frame.
> * All video frames will be unique.
> * All video frames will be decoded in order.
> * All video sources can be seeked in.
> * The user will never want to seek to non-keyframes.
> * Seeking to a position will produce the same output as decoding to a position.
> * I can seek to a specific frame number.
> * Videos have a fixed frame rate.
> * All frame timestamps are precise.
> * All frame timestamps are precise in modern formats like .mkv.
> * All frame timestamps are monotonically increasing.
> * All frame timestamps are monotonically increasing as long as you don't seek.
> * All frame timestamps are unique.
> * The duration of the final video frame is always known.
> * Users will not notice if I skip the final video frame.
> * Users will never want to play videos in reverse.
> * Users will not notice if I skip a video frame when pausing.

### Falsehoods programmers believe about video/image files
> * All video files have 8-bit per channel color.
> * All video files have 8-bit or 10-bit per channel color.
> * Fine, but at least all channels are going to have the same number of bits.
> * All samples are going to fit into a 32-bit integer.
> * Every pixel consists of three samples.
> * Every pixel consists of three or four samples.
> * Fine, every pixel consists of n samples.
> * All images files are sRGB
> * All video files are BT.601 or BT.709.
> * All image files are either sRGB or contain an ICC profile.
> * 4:2:0 is the only way to subsample images.
> * All image files contain correct tags indicating their color space.
> * Interlaced video files no longer exist.
> * I can detect whether a file is interlaced or not.
> * The chroma location is the same for every YCbCr file.
> * All HD videos are BT.709.
> * Video files will have the same refresh rate throughout the stream.
> * Video files will have the same resolution throughout the stream.
> * Video files will have the same color space throughout the stream.
> * Video files will have the same pixel format throughout the stream.
> * Fine, videos will have the same video codec throughout the stream.
> * The video and audio tracks will start at the same time.
> * The video and audio tracks will both be present throughout the stream.
> * I can start playing an audio file at the first decoded sample, and stop playing it at the last.
> * Virtual timelines can be implemented on the demuxer level.
> * Adjacent frames will have similar durations.
> * All multimedia formats have easily identifiable headers.
> * A file will never be a legal JPEG and MP3 at the same time.
> * Applying heuristics to guess the right filetype is easy.