# ajaxAlemoppo

ajaxAlemoppo is a simple library to make ajax requests.


Example:

/*

 * @ action
 * @ method
 * @ parameters
 * @ async (true: async; false: sync)
 * @ callback function 
 
 */

ajaxAlemoppo("page.html", "POST", "param1=value1&param2=value2", true, function(response){ console.log(response);});
