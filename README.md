# prismlog

prismlog is a baby utility to help you identify the possible issue with your server avoiding the hassle of multiple tmux sessions and forgetting to look at the right place for errors.

prismlog can only be used for servers which have small number of requests.

## Usage

prismlog role should be added to `site.yml` in order to create the utility on the server. All you need to do is:

`prismlog`

In order to add log files of some utility that you might be using in your product, please edit `defaults/main.yml` and update task `Create the file which contains paths to all log files` in `tasks/main.yml` accordingly.

### TODO

* Add colors to errors and warnings
* Make more options to make it customizable

If you think the utility is missing something important, please go ahead and create an issue addressing the same.

Feel free to send a PR for any important updates.
