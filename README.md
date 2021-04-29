<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Insert title here</title>
</head>
<body>
<script type="text/javascript">
function second_greatest_lowest(arr_num)
{
  arr_num.sort(function(x,y)
           {
           return x-y;
           });
  var a = [arr_num[0]];
  var b = [];
  
  for(var j=1; j < arr_num.length; j++)
  {
    if(arr_num[j-1] !== arr_num[j])
    {
      uniqa.push(arr_num[j]);
    }
  }
    result.push(uniqa[1],uniqa[uniqa.length-2]);
  return result.join(',');
  }

document.write(second_greatest_lowest([1,2,3,4,5]));




</script>

</body>
</html>
