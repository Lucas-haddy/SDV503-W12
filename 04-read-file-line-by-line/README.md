# KEY IDEAS

- fs.createReadStream(path) opens a file as a stream - data flows in chunks instead of being loaded all at once.
- crlfDelay: Infinity correctly handles Windows line endings (\r\n)
- rl.on('line', cb) is the standard event-driven way to consume lines
- rl.on('close", cb) runs when the fule has been fully read
