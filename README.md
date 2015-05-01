## [CodeIgniter](http://www.codeigniter.com/) for [Google App Engine](https://cloud.google.com/appengine/)
This repository contains a modified CodeIgniter framework and a starter app for Google App Engine.

## Installation

1. Clone the repository with

        git clone https://github.com/GoogleCloudPlatform/CodeIgniter.git

1. Follow the [PHP Tutorial](https://cloud.google.com/appengine/docs/php/gettingstarted/introduction) if you have never used App Engine before.

1. Create a CloudSQL instance based on [these instructions](https://cloud.google.com/appengine/docs/php/cloud-sql/#create). Also [create a database](https://cloud.google.com/sql/docs/create-database) for storing CodeIgniter [models](http://www.codeigniter.com/userguide2/general/models.html).

1. Replace `<project-id>`, `<instance-id>` and `<database-name>` in [app.yaml](app.yaml) with the corresponding value for your Google Cloud project and ClouSQL instance.

1. [Deploy your app](https://cloud.google.com/appengine/docs/php/gettingstarted/uploading)

1. Access your app using http://your_app_id.appspot.com and you should see CodeIgniter's default welcome page.

## Contributing
Have a patch that will benefit this project? Awesome! Follow these steps to have it accepted.

1. Please sign our [Contributor License Agreement](CONTRIB.md).
1. Fork this Git repository and make your changes.
1. Create a Pull Request
1. Incorporate review feedback to your changes.
1. Accepted!

## License
All files in this repository are under the [EllisLab License](LICENSE) unless noted otherwise.
