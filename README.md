# New
New
var params = {
  "IndexName": "explore.place",
  "Text": "Piripiri, Piauí, BRA",
  "BiasPosition": [
    -43.299999999999294,
    -7.029647446188235
  ],
  "MaxResults": 9
};
location.searchPlaceIndexForText(params, function(err, data) {
  if (err) console.log(err, err.stack); // an error occurred
  else     console.log(data);           // successful response
});
