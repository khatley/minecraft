function dataRequest(host,service)
	m.broadcast(host,service)
	_,_,_,_,_,data = event.pull("modem_message")
	m.send(client,response,data)
	print(tostring(service))
	return
end
