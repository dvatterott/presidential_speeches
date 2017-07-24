# presidential_speeches
Analysis of presidential speeches across time

Inspired by analysis of song repetitiveness by [thepudding](https://pudding.cool/2017/05/song-repetition/index.html).
Uses [Lempel-Ziv algorithm](https://en.wikipedia.org/wiki/LZ77_and_LZ78)
http://www.inference.org.uk/mackay/python/compress/#LZ
https://rosettacode.org/wiki/LZW_compression#Python

x = loaded_txt
start_size = sys.getsizeof(x) size in bytes
x_compressed = lzw(x)
end_size = sys.getsize(x_compressed)
difference = start_size-end_size

Brown, D. W. (2016) Corpus of Presidential Speeches. Retrieved from http://www.thegrammarlab.com
Grammar lab has many presidential speeches -http://www.thegrammarlab.com/?nor-portfolio=corpus-of-presidential-speeches-cops-and-a-clintontrump-corpus.
Miller center would take scraping, but also has data https://millercenter.org/the-presidency/presidential-speeches
