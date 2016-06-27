RN-redux-api-middleware
====================

Fork from [agraboso/redux-api-middleware](https://github.com/agraboso/redux-api-middleware) and makes it works on React-Native.
Only change is to remove `isomorphic-fetch` from dependencies since it will break react-native, see [https://github.com/matthew-andrews/isomorphic-fetch/pull/80](https://github.com/matthew-andrews/isomorphic-fetch/pull/80)
