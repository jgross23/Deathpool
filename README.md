<!DOCTYPE html>
<html>
<head>
<title>Name Checker</title>
<title>Death Pool or Nah</title>
</head>
<body>
<h1>Check if Name is on the List</h1>
@@ -19,9 +19,9 @@
     }
     const found = nameList.some(name => name.toLowerCase() === input.toLowerCase());
     if(found) {
       resultEl.textContent = `${input} is on the list! 🎉`;
       resultEl.textContent = `${input} is on the list! Their death will bring great riches. 🎉`;
     } else {
       resultEl.textContent = `${input} is NOT on the list.`;
       resultEl.textContent = `${input} is NOT on the list. Their death will be in vain.`;
     }
   }
</script>
