# Resum3 contracts

## TODO：

- [x] Add tag mudule to store user data
- [ ] update follow mudule
## Impl
1. setName (uint256 profileTokenID， string Name)
2. setTags(uint256 tokenID, ProfileTags  _tags)
```
struct ProfileTags {
string socialUri;
string githubUri;
uint256 contributions;
uint256 repositories;
uint256 gists;
uint256 followers;
uint256 following;
}
```

##  [testnet](https://mumbai.polygonscan.com/address/0x561C4a4aBdb202aa3Ad2730D5A1aBe4EA27f34FE#code)
