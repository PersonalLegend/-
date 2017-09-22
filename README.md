function titleCase(str) {
  var words=str.toLowerCase().split(" ");
  for (var i=0;i<words.length;i++){
    var first=words[i][0].toUpperCase();
    var ing=words[i][0];
    words[i]=words[i].replace(ing,first)； 
  }
  return words.join(" "); 
}
titleCase("h'm a little tea aoTY");





//第二种方法：

