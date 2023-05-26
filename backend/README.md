# Interview Coding Problem

This is the backend portion of the test.
We have a simple service that provides a list of random images from a remote service. 
The service is implemented in Python using FastAPI.

## Running the Service

### Dependencies
 - Python 3.11
 - Poetry


### Running the Service

To run the service, you will need to install the dependencies using Poetry:

```bash
    poetry install
    poetry shell
    make run
```


## Acceptance Criteria

- [ ] The service should return a list of images from the remote service
- [ ] The service is pretty slow, so do the necessary optimizations to make it faster
- [ ] The API is really limited and only returns 10 images at a time. Implement a way to get more images from the remote service
- [ ] Navigating into /docs it doesn't show great documentation for the API. Improve documentation for the API


### Bonus Points
- [ ] Add some tests wherever you think it's necessary
- [ ] Add a Dockerfile to run the service
- [ ] Add a persistence layer to the cache
