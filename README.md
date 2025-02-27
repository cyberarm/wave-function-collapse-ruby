# Wave Function Collapse in Ruby

![Wave Function Collapse in Ruby](assets/screenshot.png)

## Objective

Build the Wave Function Collapse algorithm in Ruby that's fast enough to iterate in a game on each frame.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

Run `bin/run` to run the example.

## Benchmark

Run `ruby test/benchmark.rb` to see how fast the algorithm is.

#### Apple M3 Max 64GB (2023): 12.437260s

    $ ruby test/benchmark.rb
    ruby 3.3.0 (2023-12-25 revision 5124f9ac75) [arm64-darwin23]
    Running benchmark for Model(grid=20x20 entropy=188)...
    12.362356   0.020133  12.382489 ( 12.437260)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/pusewicz/wave-function-collapse-ruby. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/pusewicz/wave-function-collapse-ruby/blob/main/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Credits

Tileset: https://opengameart.org/content/consolidated-hard-vacuum-terrain-tilesets
