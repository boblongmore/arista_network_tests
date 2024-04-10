# arista-network-tests

## anatomay of a test
popularized with TDD
- Arrange
- Act
- Assert
- Cleanup

## device checks
 - check for disk space to upload new image, should be 2x the amount of space the new file needs
 - check for memory leaks. Make sure memory is stable and not above 90 percent
 - check logs for errors

## system checks
- Check interfaces that should be up are up
- Check BGP is up
- Check for BGP peers
- Check for connectivity of web traffic through the network

# Authors

- Bob Longmore bob.longmore@wwt.com
