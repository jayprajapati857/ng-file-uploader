# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2021-02-10

## Added 
- Medium.com story url to Readme

## Changed
- updated latest angular version 

## [1.2.5] - 2020-08-10

### Fixed
- Security Patch.

## [1.2.4] - 2020-07-15

### Changed
- Readme.

## [1.2.3] - 2020-06-30

### Fixed
- Done event was not emitting to the output event.

### Changed
- File upload using xhr request is removed due to done event of upload output was not emitting.

## [1.2.2] - 2020-06-30

### Changed
- updated readme for updating the package.

## [1.2.1] - 2020-06-29

### Added
- Cancel uploading request.
- XHR request instead of http client request because when unsubscribing the uploading event it was not cancelling the uploading request.

## [1.2.0] - 2020-06-23

### Fixed
- Multiple files in multiple request without copying to first requests file to next request.

### Changed 
- IUploadInput formdata to data with key value pair instead of formdata. Because taking as formdata and sending to api call its copying previous requests formdata to new request also.

## [1.1.7] - 2020-06-16

### Fixed 
- Response type to any from HttpErrorResponse or HttpResponse. Though it will return only this two types of response.

## [1.1.5] - 2020-06-15

### Changed
- Readme

## [1.1.4] - 2020-06-15

### Fixed
- Fixed error event emittion.
- Fixed events emittion on invalid request id.

### Changed
- Readme
- Changed error response to HttpErrorResponse
- On rejection Http Error response will be returned

## [1.1.3] - 2020-05-03

### Changed
- param name changed from id to requestId

## [1.1.2] - 2020-05-03

### Fixed
- fixed multiple events response
- Fixed on upload first event was error

## [1.1.0] - 2020-04-29

### Added

- Facility to send headers with request

### Fixed
- Fixed on removing file it will send file and the id of deleted file
- Fixed on cancel uploading file it will send file and the id of cencelled file.

## [1.0.0] - 2020-04-29

### Added

- Added File drag drop dirctive 
- Added File select directive
- Uploading files in a single request

[1.3.0]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.5...1.3.0
[1.2.5]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.4...1.2.5
[1.2.4]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.3...1.2.4
[1.2.3]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.2...1.2.3
[1.2.2]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.1...1.2.2
[1.2.1]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.7...1.2.0
[1.1.7]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.5...1.1.7
[1.1.5]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.4...1.1.5
[1.1.4]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.3...1.1.4
[1.1.3]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.2...1.1.3
[1.1.2]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.1.0...1.1.2
[1.1.0]: https://github.com/jayprajapati857/ngx-uploader-directive/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/jayprajapati857/ngx-uploader-directive/releases/tag/1.0.0
