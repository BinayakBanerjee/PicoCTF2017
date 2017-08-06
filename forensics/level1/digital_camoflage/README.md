# PicoCTF2017
Open the file in WireShark and filter out the packets with the following string
http.request.method == "POST"
Follow up the tcp stream by right clicking on the packet
You will find the password in the header being transmitted as passwd=encodedstring
decode the value in base 64 leaving out the %3D part and there's your answer
