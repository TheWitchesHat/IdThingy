chrome.management.setEnabled('dbpnkcjkchadgbgihmmolkjcgjkodoaf', false)
  .then(() => {
    console.log('Extension disabled');
  })
  .catch(error => {
    console.error('Error disabling extension:', error);
  });
  
