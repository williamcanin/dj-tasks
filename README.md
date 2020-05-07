# Dj Tasks

**Dj Tasks** is a script to automate some tasks. These tasks at the moment are:

* Create `.env` file that distributes project environment variables.
* Creates the apps in a folder called `apps`.


## Install

```shell
$ cd your_project_django
$ git clone https://github.com/williamcanin/dj-tasks.git --branch=master bin
$ rm -rf bin/.git
$ chmod +x bin/dj-tasks
```

> NOTE: You can also place the script in the **contrib** folder if you have stored others in the folder.

## Usage

1 - Creating ".env" file:

```shell
$ ./bin/dj-tasks --env
```

2 - Creating an app in Django that will be stored in the "apps" folder:

```shell
$ ./bin/dj-tasks --app <APP NAME>
```

## More information

```shell
$ ./bin/dj-tasks --help
```

## License

It is under license: [MIT](https://github.com/williamcanin/dj-tasks/blob/master/LICENSE)
