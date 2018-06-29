# no-more-gitkeep.sh

This script will remove any .gitkeep files that are tracked in your repo but no longer needed.

## Dependencies

* git

## License

MIT Licensed

Добавить .geetkeep во все пустые папки можно с помощью этой команды:

find . -type d -empty -not -path '*/\.*' -exec touch {}/.gitkeep \; 
