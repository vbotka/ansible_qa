# Ansible Questions and Answers

The directory *tasks* keeps the source code of my answers in the
public domain. The purpose is to test the answers with the SW current
versions.

## Run all tasks

The below command runs all tasks

```console
shell> ansible-playbook pb-test.yml
```

### Suppress the OK status

The below command runs all tasks

```console
shell> ANSIBLE_DISPLAY_OK_HOSTS=false ansible-playbook pb-test.yml
```

## Run selected tasks

The below command runs selected tasks. For example, so-60525961 and so-69109062

```console
ansible-playbook pb-test-selected.yml -e s="so-60525961,so-69109062"
```
