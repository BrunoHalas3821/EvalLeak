# EvalLeak

Test-contamination detector - finds train/eval overlap via deterministic shingle matching, per-source rollups, CI-ready exit codes. Standard library only.

## How It Works

The implementation is intentionally straightforward and easy to follow.

## Configuration

Configuration is optional. Defaults are tuned for the common case; environment variables override them when needed.

## Usage

Import the module and call the exported helpers from your own code. The API is intentionally small so it is easy to embed.

## Development

Run the test suite before sending changes and keep the public surface stable.
