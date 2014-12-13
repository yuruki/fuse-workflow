task "default" do |t|
	sh "docker run -it -v $(pwd):/documents yuruki/docker-asciidoctor asciidoctor -T asciidoctor-backends/haml -r asciidoctor-diagram main.ad"
end
task "pdf" do |t|
       	sh "docker run -it -v $(pwd):/documents yuruki/docker-asciidoctor asciidoctor-pdf -r asciidoctor-diagram main.ad"
end
