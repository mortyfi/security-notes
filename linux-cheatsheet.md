## SSH
ssh-keygen -f key -N ''   — create keys without a password
key.pub — public, can be showed to every1; key — private, to no1
ssh -i key user@host      — to connect with a key

## Файлы и папки
touch file        — create an empty file
echo "text" > f   — write to the file (rewriting)
echo "text" >> f  — write in the end
mkdir -p a/b      — create folders
cp -r src dst/    — copy folder
mv src dst/       — to move
