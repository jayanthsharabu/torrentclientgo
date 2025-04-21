BitTorrent Client built on Go-lang

Decode Bencode
torrent file struct
single file
tracker struct
http tracker announce
udp tracker announce
peer wire protocol
message struct with implementation to generate correct buffers for each message
implement main loop for tcp comms with peers
multi threading
handle each peer in a thread
handle global queue of pieces and hashset of peers
file system
handle writing diff pieces of diff offsets correctly
read hashes of already existing file and remove good pieces from queue
multi writing file
beautify with nice progress bar
