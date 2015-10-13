# Mailbag

**A library for parsing maildir folders**

## Installation
### Setup
You need first to install gmime:

    sudo apt-get install golang libgmime-2.6-dev

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add mailbag to your list of dependencies in `mix.exs`:

        def deps do
          [{:mailbag, "~> 0.0.1"}]
        end

  2. Ensure mailbag is started before your application:

        def application do
          [applications: [:mailbag]]
        end

## Usage

You can use mailbag by
