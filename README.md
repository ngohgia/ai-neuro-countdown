## AI Deadlines [![Build Status](https://travis-ci.org/ngohgia/ai-neuro-countdown.svg?branch=gh-pages)](https://travis-ci.org/ngohgia/ai-neuro-countdown)

Countdown timers to keep track of CV/NLP/ML/MedicalImaging/Neuroscience conference deadlines. Each conference can be associated with both soft (i.e. internal) deadline and hard deadlines, which are useful when the countdown is set up for a specific research lab. You can add an "advisor's reminder" when a deadline is near too ;)

## Adding/updating a conference

To add or update information:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline

## Running

The website is built with Jekyll, which is a simple blogging framework built on top of Ruby on Rails. See [Jekyll's doc](https://jekyllrb.com/docs/) on how to set up Ruby/Jekyll and bundler gems.

Once the setup is done, the website can be launched locally by:
```
bundle exec jekyll serve
```

## License

MIT
