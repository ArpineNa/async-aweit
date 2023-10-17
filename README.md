# async-aweit

you need to change this function to async function .(You need to use node.js v18  in order to make work fetch)


fetchMultipleAPIs(apiUrls)
    .then(results => {
      console.log('Combined Results:', results);
    })
    .catch(error => {
      console.log('Error:', error.message);
    });


async function func(){
    try {
        const r = await fetchMultipleAPIs(apiUrls)
    return ('Combined Results:', results);
    } catch(error) {
      console.log('Error:', error.message);
    };
  }



async function fetchMultipleAPIs(apiUrls) {
    await func();
    console.log('Combined Results:', results);
    }
    func(). then (function (result) {
        console.log('Combined Results:', results);
    }).catch(error) {
      console.log('Error:', error.message);
    };
