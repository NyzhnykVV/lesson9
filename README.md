# lesson9


const person = {
    name: 'Vasyl Ivanovych',
    email: 'test@test.com',
    phone: '+380123456789',
 }
 const menu = {
     title: 'california',
     price: 70000,
     weight: '1 kg',
     'roll_number': 5,
     category: 'sushi',
     ingredients: ['rice', 'souce', 'sea fish'],
 }
  
  const menu1 = {
     title:'Philadelphia',
     price: 60000,
     weight: '0.9kg',
     'roll number': 6,
     category: 'sushi',
     ingredients: ['rice', 'nori', 'avokado', 'salmon']

    }
 
  
 

     const delivery = {
     title: 'Philadelphia',
     person: person.email,
     delivey_price: 5999, //lowest unit
     from: 'вулиця Євгена Коновальця, 35, Івано-Франківськ, Івано-Франківськ область',
     to: 'вулиця Галицька, 133, Івано-Франківськ, Івано-Франківськ область',
     status: 'new',
     error: null,
    
 }

 var arr = [menu, menu1]
 function arraySum(array){
    var sum = 0
    for(var i=0; i < array.length; i++){
        sum +=array[i];
    }
    console.log(price, delivey_price(sum));
 }
 
arraySum(arr);
